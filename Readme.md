#Configurações Globais

git config --global user.name
git config --global user.email
git config --global code.editor

#Iniciando repositório

git init

#Mexendo nos arquivos

git status
git add .
git commit -m "commit"

#Controle de versão

git log
git log --decorate
git log --author="Alan"
git shortlog
git log --graph

#Visualizando diferenças antes do commit

git diff
git diff --name-only

#Voltando para versão

git checkout Readme.md(unmodified)
git reset HEAD Readme.md(state)
git reset --soft(commit)
git reset --mixed(commit)
git reset --hard(commit)