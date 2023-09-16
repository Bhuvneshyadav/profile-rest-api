# Profiles REST API

Profiles REST API course code
.python3 -m venv venv

source ./venv/bin/activate
pip install django
django-admin startproject projectName
python manage.py runserver
python manage.py createsuperuser

python manage.py startapp appname
python manage.py makemigrations
python manage.py migrate