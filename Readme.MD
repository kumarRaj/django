This command creates a new django project 
 - django-admin startproject raj

To start a development server do:
 - cd raj
 - python manage.py runserver

The site is loaded at http://127.0.0.1:8000/

To start on a different port.
 - python manage.py runserver 8080

To run on a local network.
 - python manage.py runserver 0:8000
0 corresponds to '0.0.0.0'


To create an app:  
An app is a Web application that does something. 
A project is a collection of configuration and apps for a particular website.  A project can contain multiple apps.

 - python manage.py startapp polls
