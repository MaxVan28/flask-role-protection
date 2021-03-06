# flask-role-protection-sample
* [Create role-protection route tutorial](https://www.bryantech.me/software-development/create-flask-routes-with-roles-required-wrapper-and-flask_login/)
* Create custom roles inside Flask application to protect routes from unauthorized user
* For this sample, 2 roles are created: Admin and Customer

## Initial Setup
* Create database
```
$ python
$ from app import db
$ db.create_all()
```

* Create Virtual Environment
```
$ py -m venv venv
$ venv\Scripts\activate
```
* Install required packages

```
$ pip install -r requirements.txt
```

* Test application

```
$ flask run
```