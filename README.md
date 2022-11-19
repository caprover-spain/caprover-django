# CapRover Django

# Create project
```
$ virtualenv venv
$ source venv/bin/activate
$ pip install django
$ django-admin startproject caprover
$ python3 caprover/manage.py runserver
```

# Run docker local
```
$ docker build -t mfalconsoft/caprover-django .
$ docker push mfalconsoft/caprover-django
$ docker images
$ docker run -d -p 3000:3000 mfalconsoft/caprover-django
```