# Git e Github para iniciantes

Curso Udemy - Instrutor : Willian Justen de Vasconcellos<br>
Link para o curso: https://www.udemy.com/course/git-e-github-para-iniciantes/

## Configurações Globais

```
git config --global user.name
git config --global user.email
git config --global code.editor
```

## Iniciando repositório

```
git init
```

## Mexendo nos arquivos

```
git status
git add .
git commit -m "commit"
```

## Controle de versão

```
git log
git log --decorate
git log --author="Alan"
git shortlog
git log --graph
```

## Visualizando diferenças antes do commit

```
git diff
git diff --name-only
```

## Voltando para versão

```
git checkout Readme.md(unmodified)
git reset HEAD Readme.md(state)
git reset --soft(commit) number-commit
git reset --mixed(commit) number-commit
git reset --hard(commit) number-commit
```

- usar "git push --force" para o hard reset

## Repositório remoto

- Criar chave ssh e a seguir:

```
git remote add origin link_do_repositorio
git push -u origin master
```

## Clonando repositório

```
git clone https://github.com/AlanDeveloper/GIT-Course git-clone
```

## Branchs

```
git branch
git checkout -b test (Criar um branch)
git checkout master (Mudar de branch)
git branch -D test (Deletar um branch)
```