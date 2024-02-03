# Installation of Django and Python
Django-Course
basic step-by-step guide to creating a project app in Django along with commands to run the development server:

    Install Django (if not already installed):

pip install django

Create a Django Project:

django-admin startproject myproject

Navigate to the Project Directory:

bash

cd myproject

Create a Django App Inside the Project:

python manage.py startapp myapp

Define Models, Views, and Templates in the App (myapp):

    Define models in models.py
    Define views in views.py
    Create templates in templates/myapp/

Register the App in Project Settings (settings.py):

    Add 'myapp' to the INSTALLED_APPS list.

Run Migrations to Create Database Tables:

python manage.py makemigrations
python manage.py migrate

Create a Superuser (Optional):

python manage.py createsuperuser

Start the Development Server:

    python manage.py runserver

    Access the Development Server:
        Open a web browser and go to http://127.0.0.1:8000/ to view your Django project.

Remember to replace myproject and myapp with your desired project and app names. These commands should help you get started with a basic Django project setup and running the development server.
