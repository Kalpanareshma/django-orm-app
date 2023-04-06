# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the repository to Theia IDE.Start a new inside the project folder.

### STEP 2:
Type the appropriate code for your table and provide appropriate datatypes to the columns.

### STEP 3:
Create a report about project in readme.md file and upload the django-orm-app folder to your remote repository.

# PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class Student (models.Model):
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    referencenumber=models.CharField(max_length=20,help_text="reference number")
blood_group=models.CharField(max_length=20)
class StudentAdmin(admin.ModelAdmin):
    list_display=('name','age','email','referencenumber','blood_group')
```
## OUTPUT
![Screenshot from 2023-04-06 09-15-06](https://user-images.githubusercontent.com/122040453/230269652-c47b4d7c-816a-4c57-829a-fbc0de5c294c.png)


## RESULT
Thus,the project is developed to have Student Information Database.
