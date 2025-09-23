terminal bash

para criar o venv: python -m venv venv
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

sempre colocar a SECRET_KEY em um file (.env)