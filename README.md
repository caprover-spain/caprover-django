# CapRover Django

https://caprover.com/


```
mfalconsoft/caprover-django
```


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
$ docker run -d -p 8000:8000 mfalconsoft/caprover-django
```
