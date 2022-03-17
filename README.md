# Python + PostgreSQL + Docker
A simple and innit project for Python Env. :)

## How to use
Execute the follows steps:

``` . venv/bin/activate ```
it activate a virtual env for your application. 

``` docker-compose up --build -d ```
it get on your container with a build instruction. 

```docker-compose exec web python manage.py migrate ```
it execute the default migrations from django (auth & other stuff).

```docker-compose exec web python manage.py createsuperuser ```
it create a superuser (admin). You will need provide some information: username, password, for example.

Have fun. 


You can see your application runing on: 
```localhost:8000```

Admin area:
```localhost:8000/admin```
