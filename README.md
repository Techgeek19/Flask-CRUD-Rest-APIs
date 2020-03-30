# CRUD-Rest-APIs

## Setting up
This project was built with Python, Flask-SqlAlchemy, Marshmallow, and PostgreSQL

```
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python
>> from app import db
>> db.create_all()
>> exit()

#Runserver
$ python app.py

Then head to
http://localhost:5000 in your browser to get started.
```

# EndPoints
```
GET ==> /api/product
GET ==> /api/product/:id
POST ==> /api/product
PUT ==> /api/product/:id
DELETE ==> /api/product/:id
```
