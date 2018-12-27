### djangogirle should be in home directory  
* $ mkdir djangogirls
* $ cd djangogirls

* $ python3 -m venv myvenv
* $ source myvenv/bin/activate
* (myvenv) ~/djangogirls$ python -m pip install --upgrade pip
* (myvenv) ~/djangogirls$ pip install -r Django~=2.0.6
* (myvenv) ~/djangogirls$ django-admin startproject mysite .
* (myvenv) ~/djangogirls$ python manage.py migrate
* (myvenv) ~/djangogirls$ python manage.py runserver
* (myvenv) ~/djangogirls$ python manage.py startapp blog
* (myvenv) ~/djangogirls$ python manage.py makemigrations blog
* (myvenv) ~/djangogirls$ python manage.py migrate blog
* (myvenv) ~/djangogirls$ python manage.py createsuperuser
