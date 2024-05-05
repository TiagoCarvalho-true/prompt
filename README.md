## DIO [] Resumos Git e Github

Repositorio para armazenar  resumos sobre git e github do curso versionamento de codigo com git e github da [Digital Innovation One](https:/www.dio.me/)

# documentação 
-[Documentacao github](https://docs.github.com/en/get-started)
-[Documentacao git](https://git-scm.com/doc)


## resumo das aulas 

|Aulas|Resumos|
|-------|-------|
aula 1 e aula 2
|Gravando Alteracoes no Repositorios local|[Resumos]()|
# Comandos
```
git init 
git config
git init
git clone < URL > | --branch < branch > --single-branch
git remote add < remoto(origin) > < URL do repositório remoto >
--- adiciona um novo repositório local a partir de um repositório remoto
git status
git push -u --set-upstream < remoto(origin) > < local(main) >
--- envia para o repositório remoto(origin) as atualizações feitas localmente(main).
git pull
--- trás para o repositório local(main) as atualizações feitas no remoto(origin).
git commit -m --message < "texto do commit" > | --amend --message <"renomear commit">
git log
git add
git reset --soft | --mixed | --hard
git reflog
git restore --staged < arquivo >
git branch -v --verbose | --list | --delete
--- manipulações referentes as branches
git merge < branch para mesclar >
--- mescla as a branch escolhida na atual
git remote show origin
git fatch < repositório remoto(origin) > < repositório local(main)>
git diff
git checkout < branch > | -b
git stash pop | apply | list
--- arquiva alterações que você fez para serem trabalhadas posteriormente
