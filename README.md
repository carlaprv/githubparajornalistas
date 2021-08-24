# Github para Jornalistas

Objetivo de hoje: Neste tutorial você aprenderá como usar o Github para gerenciar seus projetos usando o Github Desktop e compartilhá-los com outros jornalistas e com o público em geral. 

Tutorial inspirado em: [Github para Periodistas](https://github.com/craft2es/githubparaperiodistas/blob/master/githubparaperiodistas.md) e [Github e Github Desktop — Básico
](https://medium.com/@gabrielcassimiro/github-e-github-desktop-b%C3%A1sico-f439879cb087)


## Git x GitHub?

### O que é Git?
Git é um sistema de código aberto e gratuito para controle de versão, criado em 2005 por Linus Torvalds enquanto desenvolvia o Kernel do Linux. Controle de versão é um sistema que permite gravar alterações em arquivos ao longo do tempo, portanto, podemos visualizar versões específicas desses arquivos posteriormente.

Geralmente, acontece de termos muitos desenvolvedores trabalhando numa mesma base de códigos, então um sistema de controle de versão como o Git é necessário para diminuir conflitos entre o código de cada desenvolvedor.

### O que é GitHub?
Se você vai utilizar Git, é necessário armazenar seu repositório em algum lugar. Existem duas formas de se fazer isso, offline, no seu próprio computador, ou online, em alguma plataforma como GitHub.

É exatamente para isso que o GitHub serve, para armazenar seus repositórios, ele é o **“Google Drive dos códigos”**.

### Por que aprender GitHub? 
+ [How journalists can get started GitHub?](https://ijnet.org/en/story/how-journalists-can-get-started-github)

+ [Getting GitHub: Why journalists should know and use the social coding site](https://knightlab.northwestern.edu/2013/06/13/getting-github-why-journalists-should-know-and-use-the-social-coding-site/)

### Como aprender GitHub? 
+ [GitHub tutorials and resources for journalists](https://www.poynter.org/news/github-tutorials-and-resources-journalists)

+ [Vídeos Github Guides (<5min cada)](https://www.youtube.com/githubguides) 

+ [Git Cheat Sheet (lista dos códigos Git por utilidade)](https://www.git-tower.com/blog/git-cheat-sheet/)

# Tutorial

### Crie uma conta no GitHub

O github não possui instalação, ele é um serviço, e caso você não tenha uma conta, chegou a hora de criá-la, [neste link](https://www.github.com/). 

![image](https://user-images.githubusercontent.com/17505036/129565796-9bb3babe-8d00-4e04-b371-a7b7b40d5b29.png)

### Crie seu primeiro repositório

Após criar a conta, você verá um botão verde `+New Repository` na qual poderá criar um repositório de acordo com a tela a seguir.

![image](https://user-images.githubusercontent.com/17505036/129565942-dd930808-de66-45dd-94f6-32a0683af722.png)

- Nomeio o repositório somente com letras minúsculas
- Inclua uma descrição breve do projeto
- Defina o repositório como público
- Escolha a opção "Initialize this repository with a README"

![image](https://user-images.githubusercontent.com/17505036/129568774-8261d76d-92ba-48a5-aa43-1c1c04b538b2.png)

Nesta imagem estamos criando um repositório cujo nome é micase, de domínio público e com o arquivo README.md embutido, que contém uma descrição do seu projeto. 

Após a criação do repositório, ele estará disponível no endereço `https://github.com/<username>/nome-repositorio`, onde username é o seu usuário do GitHub.

**Prontinho! Agora você tem o seu primeiro repositório!!!**

### Crie uma pasta onde guardará todos os seus repositórios

No seu computador, crie sua pasta de repositórios para que você não esqueça onde estão seus projetos do GitHub.

Utilize os comandos abaixo no seu **terminal**:
```bash
cd ~/Desktop
```

Para criar a pasta dentro de Desktop:
```bash
mkdir repos
```

Para listar arquivos e confirmar que a pasta foi criada:
```bash
ls
```

### Instale o github
- Opção 1: Git via linha de comando
- Opção 2: Git via interface com GitHub Desktop

## Lista de projetos de jornalismo de dados
Consulte a lista de projetos em: [https://github.com/carlaprv/githubparajornalistas/blob/main/projetos-jornalismo-de-dados.md](https://github.com/carlaprv/githubparajornalistas/blob/main/projetos-jornalismo-de-dados.md) 