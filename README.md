# TFG

## Instalation guide
 * Get python from https://www.python.org/downloads/
 * python -m pip install Django
 * pip install djangorestframework
 * pip install django-cors-headers
 * npm install -g @angular/cli

## How to run
* venv
  * cd Scripts
  * activate.bat
* backend
  * python manage.py runserver  
* frontend
  * ng serve

## Production build
* frontend
   * ng build --prod
   * cd dist/frontend
   * http-server -o
