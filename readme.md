# Django Restaurant Order Management System (DjangoROMS)

## About this application

This is a simple restaurant order management system. <br>
##### Framework: Django 1.10.1
##### Language : Python 3.6

## Install
- To change Database go to "DOMS/settings.py" and find "DATABASE = " then change database (visit here for more https://docs.djangoproject.com/en/1.10/ref/settings/#databases). Default Database is SQLite.

- Migrate Database by typing this:
```
python manage.py migrate
```
- Login:
	Username: Origa <br>
	Password: bahubali

- To Add new user go to "DOMS/urls.py" uncomment this line:
```
# url(r'^admin/', admin.site.urls),
```
by deleting "#". Then login into admin(Django administration). click Users -> add and add user. 
- Again comment this line:
```
url(r'^admin/', admin.site.urls),
``` 
to hide admin(Django administration).

## Features
- Add order
- Add products
- Export Order (pdf, excel, csv and etc)
- Edit / Delete Order
- Search Order
- Print Invoice
- Easy interface
- Mobile view

## Uses
* Restaurant Order
* Facebook Commerce
* etc...

