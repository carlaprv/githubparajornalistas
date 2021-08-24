# Opção 1: Instale o Git (linha de comando)
Para utilizar o github via linha de comando, iremos precisar instalar o Git.

## Instalação Ubuntu
Rode o comando abaixo no seu terminal:
```bash
sudo apt-get install git-all
```

## Instalação windows
Faça o download do [arquivo disponibilizado neste link](http://git-scm.com/download/win) e siga os passos de instalação.

## Instalação Mac
Faça o download do [arquivo disponibilizado neste link](https://sourceforge.net/projects/git-osx-installer/) e siga os passos de instalação.

Caso não funcione dessa forma, execute os dois comandos abaixo no seu terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
brew install git
```

## Verifique se a instalação foi feita corretamente digitando:
```bash
git version
```

Se foi instalado corretamente, no seu terminal, deve aparecer algo semelhante ao resultado abaixo:
````
❯ git --version
git version 2.30.1 (Apple Git-130)
````

## Configurando sua conta GitHub na sua máquina local
Antes de começar a usar o git, é preciso fazer as configurações iniciais da sua conta no GitHub.

Execute os comandos abaixo no seu terminal.

**Configuracão usuário**: em seguida, configure o e-mail de seu usuário no GitHub:

````bash
git config --global user.name <seu_nome_aqui>
````
Insira seu nome no local marcado: *seu_nome_aqui*.

**Configuracão e-mail**: em seguida, configure o e-mail da sua conta no GitHub:
````bash
git config --global user.email <seu@email.com>
````
Insira seu email no local marcado: *seu@email.com*.

**Verificar as configurações**: para verificar as suas configurações:
````bash
git config --list
````

A partir de agora, os arquivos serão rastreados pelo Git.
