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
  - A seta nº 1 indica o comando digitado
  - A seta nº 2 indica o endereço IP da máquina kali linux
09. clone a URL do facebook
- URL para clone ->: http://www.facebook.com
> ![Modo Usuário Padrão](./facebook.png)

### Resutados
