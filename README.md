# Django_custom_user_model
if you want to customize your default django user model you can use this application.

> How to run this Project
# Method 01
if you need full template then you can download or clone this repo. and run those commands
# Open cmd and run those commands:
```
python manage.py makemigrations 
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

# Methods 02
if you want to use only authentication application then download or clone this repo
* copy / cut authentication application
* open setting.py
* install this application on your projects
* add this line to your project settings.

AUTH_USER_MODEL = 'authentication.User'

Open cmd and run those commands:
```
python manage.py makemigrations 
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```



# Models images:
![image 01](./images%20(1).png)
![image 01](./images%20(2).png)