- [1. Django Auth0 Vue demo](#1-django-auth0-vue-demo)
- [2. Installing](#2-installing)
- [3. Screenshots](#3-screenshots)
  - [3.1. Home Page](#31-home-page)
  - [3.2. Product List Page (List and Delete)](#32-product-list-page-list-and-delete)
  - [3.3. Product Create/Update Page](#33-product-createupdate-page)

# 1. Django Auth0 Vue demo

This is an example CRUD (Create-Read-Update-Delete) application which demonstrates how to create a modern web application with a Django backend (Django REST Framework API), a Vue.js front-end and Bootstrap 4 for styling. The REST API is secured with JWT using Auth0. 

By following this simple example and the accompanying tutorial(s) you'll learn: 

* How to build a simple API using Django REST Framework
* How to add pagination to your API
* How to create, read ,update and delete database records 
* How to add JWT authentication to your API using Auth0
* How to build a front-end application with Vue.js 
* How to consume a REST API from a Vue.js application (using Axios)
* How to create authentication guards for your views
* How to integrate Django, Webpack and Vue.js for development and production 

# 2. Installing

You need to have `virtualenv` and Python 3 installed (Django 2 requires Python 3) then:

First create a new virtual environment and activate it with:

```bash
virtualenv -p python3 env
source env/bin/activate
```

Next, clone the project from Github:

```bash
git clone https://github.com/techiediaries/django-auth0-vue
cd django-auth0-vue
```

Install the project requirements using pip:

```bash
pip install -r requirements.txt
```

If the installation of the `cryptography` package fails make sure to install the `python3-dev` package. In Ubuntu you can use the following command:

```bash
sudo apt-get install python3-dev
``` 

Next install the Vue.js dependencies and run the front-end dev server with:

```bash
cd vueapp
npm install
npm run dev
```

Finally migrate the database then run the Django dev server with:

```bash
python manage.py migrate
python manage.py runserver
``` 

You can now navigate with your web browser to http://localhost:8000 and start playing with the demo.


# 3. Screenshots

## 3.1. Home Page

## 3.2. Product List Page (List and Delete)

![]()

## 3.3. Product Create/Update Page

![]()

![]()

