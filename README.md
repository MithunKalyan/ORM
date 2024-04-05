# Ex02 Django ORM Web Application
## Date: 5.04.24

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```html
admin.py

from django.contrib import admin
from .models import Employee
admin.site.register(Employee)

models.py

from django.db import models

class Employee(models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=20)
    dept=models.CharField(max_length=20)
    salary=models.FloatField()
    aadhaar=models.BigIntegerField(null=True)
```

## OUTPUT

![outtt](https://github.com/MithunKalyan/ORM/assets/148410106/e057f70b-c726-4293-b7a7-e6aaf7889bde)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
