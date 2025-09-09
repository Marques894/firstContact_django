## 🛠️ 1. Criar ambiente virtual
### Instalar o virtualenv
 - pip install virtualenv

### Criar o ambiente virtual (nome: 'venv')
 - py -m venv venv

## 🚀 2. Ativar\ambiente virtual
### Ativar
  - .\venv\Scripts\Activate

### Desativar (caso precise)
  - deactivate

## 📦 3. Instalar Django
  - pip install django
  - pip freeze > requirements.txt

## 📁 4. Criar pasta do projeto e entrar nela
  - mkdir feriados
  - cd feriados

## 🏗️ 5. Criar projeto Django (fora da pasta venv)
  - django-admin startproject feriados .

## ⚡ 6. Rodar migrações iniciais
  - python manage.py migrate

## 🖥️ 7. Rodar servidor
  - python manage.py runserver

## 🌐 8. Acessar projeto

Site: http://127.0.0.1:8000/
