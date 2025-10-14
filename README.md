terminal bash

para criar o venv: python -m venv .venv
para iniciar o ambiente: source venv/Scripts/activate
para desativar: deactivate 

biblioteca
pip install requests

verificar se baixou
pip freeze

verificar tudo instalado 
pip freeze > requirements.txt

baixar o django
pip install django

inicializar o projeto com django
django-admin startproject setup .

subir o servidor
python manage.py runserver 

para carregar variáveis de ambiente a partir de um arquivo .env
pip install python-dotenv

sempre colocar a SECRET_KEY em um file (.env)

para ver todas as funçao com a tag manege.py
python manage.py help

se der algum warning no (folder setup) (file setting.py) (from dotenv import load_dotenv) verificar se realmente esta no ambiente virtuar == (.venv\Scripts\python.exe)

para criar o app = uma aplicaçao 
python manage.py startapp "nome da pasta do app"


para criar criar as migraçoes e alocar 
python manage.py makemigrations
python manage.py migrate

rodar terminal shell nativamente
python manage.py shell

adicionar no banco via terminal shell nativo
nome_do_item = nome_da_Classe(todos os dados da classe)

para salvar 
nome_do_item.save()

para mostrar os itens
Fotografia.objects.all()