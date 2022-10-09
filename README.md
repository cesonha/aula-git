# Aprendendo git

## Clonando um repositório

Primeiro passo, clonar um repositório usando https

Segundo passo, aprender a criar uma chave e configurar SSH github

Terceiro passo, trocar a url remota de https para ssh

## Commitando mudanças

Depois de editar os arquivos desejados, é necessário adicioná-los ao ambiente de staging com o comando `git add nome_do_arquivo`

As mudanças adicionadas ao ambiente de staging são adicionadas à uma nova versão do repositório através de commits, commits são como 'fotografias' de um estado dos arquivos num determinado momento. Cada commit possui um hash de identificação, e um commit sempre possui um parent commit, fazendo com que sempre exista uma "árvore genealógica" das mudanças dentro de um repositório.

Para commitar os arquivos que estão no atual ambiente de staging, usamos o comando `git commit -m "mensagem descrevendo as mudanças"`

Learning shortcuts: como podemos, em apenas um comando, adicionar todos arquivos modificados ao ambiente de staging e já commitar essas mudanças?

## Status

## Diff

## Log

## Criando branches

Num repositório git, é possível criar um branch (galho) dessa árvore de commits para que mudanças sejam feitas sem afetar o branch main. Usamos o comando `git branch nome_do_novo_branch`, para criar esse novo branch, seguido do comando `git checkout nome_do_novo_branch`, que muda o atual branch em que estamos trabalhando localmente para esse branch recém criado.

Learning shortcuts: como podemos, em apenas um comando, criar um novo branch e já mudar o branch local para começar a trabalhar nele?


## Stash

## Reset

### Hard

### Mixed

## Merge

## Rebase


Vinicius Riso

veve
