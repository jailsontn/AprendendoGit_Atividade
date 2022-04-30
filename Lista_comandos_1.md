# Comandos GIT

## Criar novo repositório local

git init

## Clonar um repositório remoto

git clone

## Verificando os Status de Seus Arquivos

git status

## Rastreando Arquivos Novos

git add [arquivo]

## Preparando Arquivos Modificados

git add [arquivo]

## Status Curto

git status -s

## Visualizando Suas Alterações Dentro e Fora do Stage

git diff
git diff --cached ou git diff --staged

## Fazendo Commit das Suas Alterações

git commit

## Pulando a Área de Stage

git commit -a

## Removendo Arquivos

git rm
git rm --cached

## Movendo Arquivos

git mv

## Vendo o histórico de Commits

git log –pretty=oneline --graph

## Desfazendo as coisas

git commit --amend

## Retirando um arquivo do Stage

git reset HEAD CONTRIBUTING.md

## Desfazendo as Modificações de um Arquivo

git checkout -- CONTRIBUTING.md