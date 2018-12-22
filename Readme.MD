# Django Basics
The aim is to teach Django to a small group of people.
- ```mysite``` is a basic example of how ```views.py, urls.py and django templating``` works.
- ```myapp``` is an example of how ```forms.py, models.py, admin.py, views.py, urls.py and django templating``` works. 
This is more relatable to the development progress in Django.

## Installation
- Make a virtual environment by running ```python -m venv myvenv```
- Activate the virtual environment by:
  - ```myvenv\Scripts\activate``` on Windows
  - ```source myvenv/bin/activate``` on MacOS, Linux, Ubuntu
- Run ```pip install django```
- ```cd mysite``` or ```cd myapp```
- ```python manage.py makemigrations app```
- ```python manage.py migrate```
- ```python manage.py runserver```
