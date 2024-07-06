# blog-in-py

I am learning building Blog site using Python Django from different Video Courses, Books, and Websites.

In Django, a project is considered a Django installation with some settings. An application is a group of models, views, templates, and URLs. Applications interact with the framework to provide specific functionalities and may be reused in various projects.

## Few Commands

```powershell
py -m venv .venv
python.exe -m pip install --upgrade pip

python -m pip install Django~=5.0.4
python -m django --version

django-admin startproject blogposts

cd blogposts
python manage.py migrate

python manage.py runserver

python manage.py runserver 127.0.0.1:8001 --settings=mysite.settings

python manage.py startapp blog

D:\TSA\blog-in-py\blogposts> python manage.py makemigrations blog
D:\TSA\blog-in-py\blogposts> python manage.py sqlmigrate blog 0001
D:\TSA\blog-in-py\blogposts> python manage.py migrate

D:\TSA\blog-in-py\blogposts> python manage.py shell
shell>>> 
```

## Few Points

> 1. Django follows the MTV (Model-Template-View) pattern.
> 1. Model: This defines the logical data structure and is the data handler between the database and the view.
> 1. Template: This is the presentation layer. Django uses a plain-text template system that keeps everything that the browser renders.
> 1. View: This communicates with the database via the model and transfers the data to the template for viewing.
