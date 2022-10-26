# django-create-project-and-app
## create project
```
django-admin startproject PROJECTNAME
```
## create virtual environment
```
python -m venv venv
```
## activate virtual environment
### linux
```
source venv/bin/activate
```
### windows
```
venv/Scripts/activate
```
## install django in venv
```
python -m pip install django
```
## Requirements
### Freeze
```
pip3 freeze > requirements.txt
```
### Install
```
pip install -r requirements.txt
```
## runserver
```
python manage.py runserver
```
## Create App
```
python manage.py startapp APPNAME
```
* Write app name in INSTALLED_APPS in "settings.py" file
* Create Template
* Write View
* Create URL

## Run Shell
```
python manage.py shell
```
## Import model in shell
```
from APPNAME.models import CLASSNAME
```
## Create Super User
```
python manage.py createsuperuser
```
