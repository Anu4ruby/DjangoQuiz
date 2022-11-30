# DjangoQuiz
This website is built using Django 3.2.3 and Python 3.
to use this website- download the code. create a vitual environment (optional). Assuming Mac terminal,
do - pip install django==3.2.3
python manage.py makemigrations (view the tables that will be created)
python manage.py migrate (create tables user and quiz)
python manage.py createsuperuser
enter your username password, press y if you want to bypass warnings of weak password
python maange.py runserver
got to  http://127.0.0.1:8000/admin/
login using your superuser username/password
go to quiz model and add questions and multiple choice answers
your site is ready to use
Code snippets has been used from -  https://data-flair.training/blogs/create-quiz-application-python-django/
