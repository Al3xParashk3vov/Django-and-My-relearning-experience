# Django-and-My-relearning-experience
Im trying relearn django, since I haven't used it in a year.

# The commands that you need to use on a daily basis 

## Starting a new project:

### Create Python virtual env 
python -m venv venv

### Activate virtual env
.\venv\Scripts\activate    

### Install django
pip install django

### New django project
django-admin startproject (Project Name)

### Create app
python manage.py startapp (App Name)

### Saving and running project
python manage.py makemigrations /
python manage.py migrate /
python manage.py runserver / 
pip freeze > requirements.txt / 
pip install -r requirements
