
# [Django](https://www.djangoproject.com/) in [Python](https://www.python.org/)

[![alt text](image/django_python_icon.png)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)

#### [Django](https://www.djangoproject.com/) is a full stack web framework that allows for rapid development of websites.

-----------------------------------------------------------

#### Command settings _(Terminal, Shell)_:

1) Command install [Django](https://www.djangoproject.com/):
[![alt text](image/django_icon.png)](https://www.djangoproject.com/)

```
pip3 install django
```

2) Create a _'mysite'_ project folder:
```
django-admin startproject mysite
```

3) Run server in _'mysite'_ project:
```
cd mysite

python3 manage.py runserver
```

4) Start app _'main'_ in project: 
```
python3 manage.py startapp main
```

5) Get into site directory in project:
```
python3 manage.py migrate
```

6) Make migrations with te name of our app is _'main'_ (to tell django that we've modified the models):
```
python3 manage.py makemigrations main
```
- To make it apply 'main':
```
python3 manage.py migrate
```

