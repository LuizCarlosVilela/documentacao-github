
## **:computer: Documentação para Git e GitHub**

### **_🛠 Configurações Iniciais_**

#### Baixando e Instalando o Git
- Primeiramente é preciso baixar o Git na sua máquina, para ***Mac/Windows/Linux*** basta clicar nesse <kbd>[LINK](https://git-scm.com/download)</kbd> e seguir as instruções de download e instação do seu sistema operacional, **como podemos visualizar na imagem abaixo**.

<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143149450-c1d92a92-833d-43f0-a8be-90429a820548.PNG" width="600px" />
</div>

#### Criando conta GitHub

- Agora vamos criar uma conta em um servidor de repositórios remotos. Nesse caso acessaremos o [GitHub](https://github.com/) e criaremos uma conta normalmente **Clicando em Sign in e depois Create an account**.
<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143150820-9a3b3587-ce50-4d5b-b131-73639fd7174a.PNG" width="600px" />
</div>

#### Configurando ambiente
- Após criarmos a nossa conta vamos configurar nosso Git local com esses dados, rodando os seguintes comandos no terminal:

##### - ***Configurando usuário e e-mail***
```
git config --global user.name "Fulano de Tal"
```
```
git config --global user.email "your_email@example.com"
```

##### - ***Listando todas as configurações***
```
git config --list
```
