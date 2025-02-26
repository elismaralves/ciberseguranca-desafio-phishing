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

> ![Modo Usuário Padrão](./ResultadoDiferente.png)

- Veja as imagens a seguir:
> ![Modo Usuário Padrão](./Clone_Facebook3a.png)
> 
> ![Modo Usuário Padrão](./Clone_Facebook3b.png)


Agora, caso você queira ver a exibição do login e senha, você pode seguir os passos abaixo:

### Obs.:
* Os passos do 1 (um) ao 6 (sexto) são iguais aos descritos acima, mudaremos as opções a partir do sétimo passo.

1. Entre no terminal de comando do kali linux
2. Mude do usuário padrão para o usuário root
3. Iniciando o setoolkit - comando ->: ``` setoolkit ```
4. Selecione o tipo de ataque: ``` Social-Engineering Attacks ``` - opção ->: ``` 1 ```
5. Selecione o Vetor de ataque: ``` Web Site Attack Vectors ``` - opção ->: ``` 2 ```
6. Método de ataque: ```Credential Harvester Attack Method ``` - opção ->: ``` 3 ```
7. Método de ataque: ``` Web Templates ```
- Método de ataque - opção ->: ``` 1 ```
> ![Modo Usuário Padrão](./WebTemplate_Google1.png)
8. Selecione um template
- Template - opção ->: ``` 2 ```
> ![Modo Usuário Padrão](./WebTemplate_Google2.png)
9. Aguarde o kali linux carregar o template
> ![Modo Usuário Padrão](./WebTemplate_Google2b.png)
10. Acesse através de um navegador de uma outra máquina (host) que esteja na mesma rede utilizando o IP da máquina kali linux.
> ![Modo Usuário Padrão](./WebTemplate_Google2c.png)


### Resutados
 
> ![Modo Usuário Padrão](./WebTemplate_Google2d.png)
