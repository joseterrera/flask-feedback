Below are the steps that should get one started using the app:

### Create a Virtual Environment

```console
$ python3 -m venv venv
$ source venv/bin/activate
```

### Install pachackes in requirements.txt
```console
pip3 install -r requirements.txt
```

### Packages installed (installing everything on requirements.txt will install these packages)
```console
pip3 install flask
pip3 install flask-debugtoolbar
pip3 install psycopg2-binary
pip3 install flask-sqlalchemy
pip3 install flask_wtf
pip3 install bcrypt
```

### Create a database

```console
createdb flask-feedback
```

### To run the app:

```console
flask run 
```
