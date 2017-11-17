# jeanettiesblog

This is my Django/Python blog that demonstrates CRUD funtionality for my CodeLouisville class. 

I currently have it hosted at http://jeanettie.pythonanywhere.com/. I have made a staff user that you can use to log in in order 
to experience the add new post, delete, delete confirm, and edit pages. go to http://jeanettie.pythonanywhere.com/admin/ log in using
username: codelouisville, password: djangopython. Once in the admin you can click on "view site" at the top right. Then feel free to explore 
the site.

To pull from git hub. Fork and/or clone this repository. 

1. From the jeanettiesblog folder enter the following into the command line in order to start the virutal enviroment:
$ virtualenv --python=python3.6 myvenv
$ source myvenv/bin/activate

2. Next install Django using pip. 
(myvenv) ~$ pip install --upgrade pip
(myvenv) ~$ pip install django~=1.11.0

3. To runserver, enter the following into the command line:
(myvenv) ~$ python manage.py runserver
