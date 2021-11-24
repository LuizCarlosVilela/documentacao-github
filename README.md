
# **:computer: Documentação para Git e GitHub**

<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143158536-02f6f3ee-9702-48dd-998b-b628f12ce18c.gif" alt="logo-github" width="600px" />
</div>

## **_🛠 CONFIGURAÇÕES INICIAIS_**

#### Baixando e Instalando o Git
- Primeiramente, é preciso baixar o Git na sua máquina, para ***Mac/Windows/Linux*** basta clicar nesse <kbd>[LINK](https://git-scm.com/download)</kbd> e seguir as instruções de download e instalação do seu sistema operacional, **como podemos visualizar na imagem abaixo**.

<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143149450-c1d92a92-833d-43f0-a8be-90429a820548.PNG" alt="logo-github" width="600px" />
</div>

#### Criando conta GitHub

- Agora vamos criar uma conta em um servidor de repositórios remotos. Nesse caso acessaremos o [GitHub](https://github.com/) e criaremos uma conta normalmente **Clicando em Sign in e depois Create an account**.
<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143150820-9a3b3587-ce50-4d5b-b131-73639fd7174a.PNG" alt="logo-github" width="600px" />
</div>

#### Configurando ambiente
- Após criarmos a nossa conta vamos configurar nosso Git local com esses dados, rodando os seguintes comandos no terminal:

##### ***# Configurando usuário e e-mail***
```
git config --global user.name "Fulano de Tal"
```
```
git config --global user.email "your_email@example.com"
```

##### ***# Listando todas as configurações***
```
git config --list
```
## **_👾 CRIANDO E MANIPULANDO REPOSITÓRIOS_** <code><img height="27" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="git"></code> 

#### Comandos para criação e manipulação de repositórios

##### ***# Criando repositório local***
```
git init 
```

##### ***# Adicionando tudo ou um arquivo específico nesse repositório***
```
git add * ou git add README.md 
```

##### ***# Salvando arquivos adicionando a um comentário (commit)***
```
git commit -m "first commit"
```

##### ***# Criando e passando para branch local default***
```
git branch -M master
```

#### Criando repositório remoto 

- Após criar o repositório local, vamos criar um repositório remoto na nossa conta do [GitHub](https://github.com/) para depois conseguirmos sincronizar ambos os repositórios.
<div align="center">
  <img src="https://user-images.githubusercontent.com/57350762/143156013-a092085a-99cf-45b9-a184-cc3873c1fb70.PNG" alt="logo-github" width="600px" />
</div>

#### Comandos para sincronizar e subir versão do código

##### ***# Sincronizar repositórios***
```
git remote add origin <url_repositorio_remoto>
```

##### ***# Subir código local para repositório remoto***
```
git push -u origin master
```

## ***:books: REFERÊNCIAS***

- [Git](https://git-scm.com/docs/gittutorial)
- [GitHub](https://github.com/)

<i><h2 align="center">Feito com ❤️ por <a href="https://www.linkedin.com/in/luiz-carlos-vilela/">Luiz Carlos Vilela</a></h2></i>
