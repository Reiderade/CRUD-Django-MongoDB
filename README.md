# Django-MongoDB-CRUD

Basic create, read, update and delete for students marks and total is here with super cool User Interface. MongoDB, A NoSQL database is used to store data.
A Restful web service for accessing the students details is created.

## Dependencies
-- Djongo `pip install djongo`  
-- [MongoDB](https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-4.4.2-signed.msi)  
-- Django Rest Framework `pip install djangorestfamework`  

## Start the MongoDB server
First we need to create the db directory where the database files will live in. In your terminal navigate to the root of your system by doing `cd..` until you reach the top directory. You can create the directory by running `mkdir /data/db`. Now open a different tab in your terminal and run `mongod` to start the Mongo server.

## Run
Go to the project directory and run `python manage.py runserver`

## Access REST API
`/students` retrieves all student details  
`/students/<id>` retrieves details of that particular student

## Screenshot
![CRUD](https://github.com/rishi772001/django-mongodb-crud/blob/main/screenshots/Capture.PNG)
---
![REST API](https://github.com/rishi772001/django-mongodb-crud/blob/main/screenshots/Capture1.PNG)


