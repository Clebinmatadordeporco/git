# GIT

## Acessar 
>Chrome git-scm.com

## Realizar Donwload do GIT, versão atual 2.43.0

## Instalar o GIT, seguindo o padrão do instalador (Next-Next)

## Verificar versão instalada
> git -v  
>
    //git version 2.43.0.windows.1

## Criar ou escolher um diretório para configurar o repositório do git
> mkdir projeto

## Acesse o diretório
> cd projeto

## Inicializar o armazenamento em repositório git
> git init
> 
    //Initialized empty Git repository in projeto/.git/

## Configurar os dados de usuário
> git config --local user.name "Usuario"

> git config --local user.email "usuario@dominio.com.br"


## Verificar mudanças
> git status

## Preparar as mudanças para serem salvas

#### Para preparar apenas um arquivo
> git add file
#### Para preparar todos os arquivos (quando queremos todos os arquivos)
> git add .


## Salvar as Mudanças (commit)
> git commit -m "Mensagem do Commit"
>
    O Parametro "-m" define que estamos informando uma mensagem referente aos códigos que estamos salvando.

    ##Remover login do terminal
    > git config --unset-all user.name

    > git config --unset-all user.email
    
    > git config --unset-all credential.helper
