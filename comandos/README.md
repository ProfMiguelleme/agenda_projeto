Iniciar o projeto Django

```
python -m venv .venv
. venv/bin/activate
pip install django
django-admin startproject project .
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main

# Configure o .gitignore
#Link para copiar os dados do GitIgnore
#https://djangowaves.com/tips-tricks/gitignore-for-a-django-project/

git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT

git push
```
