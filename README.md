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

## Tutorial

## 1. Crie uma conta no GitHub

O github não possui instalação, ele é um serviço, e caso você não tenha uma conta, chegou a hora de criá-la, [neste link](https://www.github.com/). 

![image](https://user-images.githubusercontent.com/17505036/129565796-9bb3babe-8d00-4e04-b371-a7b7b40d5b29.png)

## 2. Crie seu primeiro repositório

Após criar a conta, você verá um botão verde `+New Repository` na qual poderá criar um repositório de acordo com a tela a seguir.

![image](https://user-images.githubusercontent.com/17505036/129565942-dd930808-de66-45dd-94f6-32a0683af722.png)

- Nomeio o repositório somente com letras minúsculas
- Inclua uma descrição breve do projeto
- Defina o repositório como público
- Escolha a opção "Initialize this repository with a README"

![image](https://user-images.githubusercontent.com/17505036/129568774-8261d76d-92ba-48a5-aa43-1c1c04b538b2.png)

Nesta imagem estamos criando um repositório cujo nome é micase, de domínio público e com o arquivo README.md embutido, que contém uma descrição do seu projeto. 

Após a criação do repositório, ele estará disponível no endereço `https://github.com/<username>/site`, onde username é o login que você usou para se cadastrar. Acessando esta url temos a seguinte resposta:

## Prontinho! Agora você tem o seu primeiro repositório

Agora, vamos ver como salvar o repositório no seu computador.
![image](https://user-images.githubusercontent.com/17505036/129568811-ac6071fa-f2b9-4dec-b085-30ed77eff78f.png)


## 4. Crie uma pasta onde guardará todos os seus repositórios

Sugestão: utilize o nome `repos`.

Crie sua pasta de repositórios para que você não esqueça onde estão seus projetos.
Quando você copiar seu repositório do Github para o seu computador, salve o repositório dentro da pasta `repos`.
![image](https://user-images.githubusercontent.com/17505036/129566724-09d70bb1-0276-41a3-a415-a3ca59bb3510.png)

## 5. Instale o Git e Github 

### Opção 1: Github via linha de comando
Para utilizar o github via linha de comando:

* siga o tutorial: [Instalando e Configurando o Git no Windows, Linux e Mac
](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) ou [Instalando, configurando e inicializando o Git no Linux]( https://dev.to/womakerscode/instalando-configurando-e-inicializando-o-git-no-linux-2m96)
* pule para a seção [Lista de projetos de jornalismo de dados recomendados](https://github.com/carlaprv/githubparajornalistas#lista-de-projetos-de-jornalismo-de-dados-recomendados)

![image](https://user-images.githubusercontent.com/17505036/130127514-eec92fee-3a6e-4540-881a-3d1f69e75e89.png)


### Opção 2: Github Desktop
Se você prefere utilizar a versão do GitHub Desktop com interface gráfica, siga os próximos passos 6, 7, 8 e 9.

![image](https://user-images.githubusercontent.com/17505036/130127576-9da4080f-4ae3-4bec-bd6b-66f6e8631a29.png)

Bem, o Github Desktop é a ferramenta mais rápida e fácil para baixar seus repositórios.

Baixe o [Github Desktop](https://desktop.github.com/) e instale-o.

Clique no ícone Github Desktop e quando o aplicativo abrir, vá para o menu superior esquerdo e clique em Preferências.

Se tiver dúvidas, consulte os [guias disponibilizados](https://docs.github.com/pt/desktop/contributing-and-collaborating-using-github-desktop).

## 6. Clone (copie) seu repositório para seu computador com Github Desktop

Na barra lateral esquerda do Github Desktop você deve ver a lista de repositórios que você criou.
Caso não veja, pode buscar a opção de [clonar](https://docs.github.com/pt/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop).

## 7. Salve o repositório clonado em sua pasta repos

Quando você clona e salva o repositório na pasta de repositórios `repos`, o que você está fazendo é baixar para o seu computador uma cópia do repositório que estava hospedado em Github.com.

## 8. Seu primeiro repositório e seu primeiro "Commit"
Git e Github controlam todas as mudanças que você faz em seu repositório (se você deletou um arquivo, editou um texto, alterou uma planilha, adicionou uma foto, etc).

O objetivo é que você possa conhecer e identificar todas as mudanças importantes que você faz e ter as diferentes versões. Algo como manter um changelog de todos os rascunhos que você escreve até que seu relatório seja publicado.

Mas ... para facilitar a identificação das alterações, você deve informar ao Github que as fez e publicá-las. Isso é chamado de "Confirmar alterações" --> "Commit".

A regra é fazer um commit a cada alteração realizada com muita frequência e explicar resumidamente quais mudanças você fez.

- Faça uma alteração no arquivo `README.md` adicionando um título e descrição

## 9. Resultado

![image](https://user-images.githubusercontent.com/17505036/129568620-0b73ec38-d3eb-494c-8db2-3e378f623bdf.png)

# Lista de projetos de jornalismo de dados recomendados
Consulte a lista de projetos em: [https://github.com/carlaprv/githubparajornalistas/blob/main/projetos-jornalismo-de-dados.md](https://github.com/carlaprv/githubparajornalistas/blob/main/projetos-jornalismo-de-dados.md)
