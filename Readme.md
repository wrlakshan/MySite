## create virtual environment

- virtualenv env

## activate the virtual environment

- source env/Scripts/activate

## install django

- pip install django

## create project called study in root directory

- django-admin startproject study .

## start server

- python manage.py. runserver 8080
- python manage.py runserver 0.0.0.0:8000

## create application

- python manage.py startapp polls

## looks at the INSTALLED_APPS setting and creates any necessary database tables according to the database settings in your mysite/settings.py

- python manage.py migrate
