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
## Create App
```
python manage.py startapp APPNAME
```
* Write app name in INSTALLED_APPS in "settings.py" file
* Create Template
* Write View
* Create URL
## Import model in shell
```
from APPNAME.models import CLASSNAME
```
## Run Server
```
python manage.py runserver
```
## Run Shell
```
python manage.py shell
```
## Create Super User
```
python manage.py createsuperuser
```
