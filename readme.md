Python-Django based online event platform named stegolica

> Hosting can be done at openshift and webapp is optimised for that.

New to this
----------  
go to wsgi and create a virtualenv

`cd wsgi`
`virtualenv venv`
`source venv/bin/activate`

create a database

`createdb stegolica`

enable settings, fill in your username and password in settings.py

`cd stegolica`
`cp dev-settings.py settings.py`

Run it

`python manage.py runserver`

go to `127.0.0.1:8000` to view


> for deployment i openshift use dev.py.

Wanna help
---------
you can help by

1. finding out issues
2. fixing issues already in the issues section

Template design
--------------

![alt text](http://i.imgsafe.org/87195dec93.png)
![alt text](http://i.imgsafe.org/871922cf5d.png)
![alt text](http://i.imgsafe.org/87192a34df.png)
![alt text](http://i.imgsafe.org/879d151076.png)
