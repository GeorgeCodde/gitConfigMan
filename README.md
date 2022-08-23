## Comandos para iniciar la configuración de GIT en una maquina

```git
git --version

git config --global user.name "Jorge Lopez Sanchez"
git config --global user.email jorgels120878@gmail.com
git config --global core.editor "code --wait"
git config --global init.defaultBranch main
git config --global -e
git config --global core.autocrlf input

```

## Comandos para clonar un proyecto

```git
git clone <url del repositorio>
```

## Comandos para subir archivos a un repositorio de github

### Primero iniciar el git local y hacer el primer commit

```git
git init
git status
git add <archivos>
git commit -m "Mensaje de commit"
git barnch -M main
git remote add origin <Url del repositorio>
git push -u origin main
```
