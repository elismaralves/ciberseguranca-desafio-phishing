# Cibersegurança Desafio Phishing

# (Phishing para captura de senhas do Facebook)


### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux (Passo a passo)

01. Entre no terminal de comando do kali linux
- Terminal do kali linux em modo usuário padrão:
> ![Modo Usuário Padrão](./ModoUsuárioPadrão.png)
02. Mude do usuário padrão para o usuário root
- Acesso root - comando ->: ``` sudo su ```
> ![Modo Usuário Padrão](./ModoRootComando1.png)
- Digite a senha:
> ![Modo Usuário Padrão](./ModoRootComando2.png)
- Agora seu prompt indica o modo root:
> ![Modo Usuário Padrão](./ModoRootComando3.png)
03. Execute a ferramenta setoolkit
- Iniciando o setoolkit - comando ->: ``` setoolkit ```
> ![Modo Usuário Padrão](./Setoolkit1.png)
- setoolkit em execução:
> ![Modo Usuário Padrão](./Setoolkit2.png)
04. Selecione o tipo de ataque: ``` Social-Engineering Attacks ```
- Tipo de ataque - opção ->: ``` 1 ```
> ![Modo Usuário Padrão](./Setoolkit4.png)
05. Selecione o Vetor de ataque: ``` Web Site Attack Vectors ```
- Vetor de ataque - opção ->: ``` 2 ```
> ![Modo Usuário Padrão](./Setoolkit6.png)
06. Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque - opção ->: ``` 3 ```
> ![Modo Usuário Padrão](./Setoolkit8.png)
07. Método de ataque: ``` Site Cloner ```
- Método de ataque - opção ->: ``` 2 ```
> ![Modo Usuário Padrão](./Setoolkit10.png)
08. Obtendo o endereço da máquina kali linux
- Obtendo o endereço da máquina - comando ->: ``` ifconfig ```
> ![Modo Usuário Padrão](./ifconfig2.png)
  - A seta nº 1 indica o comando ifconfig digitado
  - A seta nº 2 indica o endereço IP da máquina kali linux
09. clone a URL do facebook
- URL para clone ->: http://www.facebook.com
> ![Modo Usuário Padrão](./Facebook1.png)
10. Aguarde a clonagem da página do facebook pelo kali linux 
> ![Modo Usuário Padrão](./Clone_Facebook1.png)
11. Acesse através de um navegador de uma outra máquina (host) que esteja na mesma rede utilizando o IP da máquina kali linux.
> ![Modo Usuário Padrão](./Clone_Facebook2.png)
> >

### Resutados

- O resultado difere do exibido no vídeo do Cassiano Peres, isso se dá, por conta do facebook utilizar de boas práticas para tentar defender os campos de login e senha via scripts de codificação 64 e hashing como citado no artigo: https://www.dio.me/articles/sobre-o-setoolkit-e-o-facebook


- Veja as imagens a seguir:
> ![Modo Usuário Padrão](./Clone_Facebook3a.png)
> 
> ![Modo Usuário Padrão](./Clone_Facebook3b.png)


Agora, caso você queira ver a exibição do login e senha, você pode usar estes passos:

* Ao executar os passos de 1 até o 6 conforme descrito abaixo, mudaremos as opções a partir do sétimo passo.
01. Entre no terminal de comando do kali linux
02. Mude do usuário padrão para o usuário root
03. Iniciando o setoolkit - comando ->: ``` setoolkit ```
04. Selecione o tipo de ataque: ``` Social-Engineering Attacks ``` - opção ->: ``` 1 ```
05. Selecione o Vetor de ataque: ``` Web Site Attack Vectors ``` - opção ->: ``` 2 ```
06. Método de ataque: ```Credential Harvester Attack Method ``` - opção ->: ``` 3 ```
7. 






> >
- URL para clone ->: http://www.facebook.com
> ![Modo Usuário Padrão](./WebTemplate_Google1.png)


