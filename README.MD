# Flask Login Boilerplate

A boilerplate to easily and fast start a new flask web app project.

### Installing

Run in virtual environment. 
(http://raspberrypi-aa.github.io/session4/venv.html)

```
Install required libraries:

pip install flask flask-sqlalchemy flask-login
```
Create the database.

from project import db, create_app
db.create_all(app=create_app())

```
Build the project.

export FLASK_APP=project
export FLASK_DEBUG=1
flask run
```

## Built With

* Python (https://www.python.org/)
* Flask (https://flask.palletsprojects.com/en/1.0.x/)

## Authors

* **David Szemenkar**
