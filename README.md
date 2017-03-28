### Instant Flask/Python kit ready to be deployed
 

### Application Architecture:

- Flask/Python
    - Models
    - Views
    - Authentication
- PostgreSQL
- jQuery
- Jinja2
- Materialize.css

## Local Setup

Please fork this repository and clone it to your computer so you can use it as the base for your project.


### 1. Flask

**Activate your environment by running the following from your project directory in your shell:**

```
. venv/bin/activate
```

**In the future when you want to go back to the real world, use the following command**

```
deactivate
```

Now that your work environment is activated.

**Now that your work environment is activated, run the following from your project directory in your shell:**

```
pip install -r requirements.txt
```

**All that is left is to start your server and you will have a fully working full stack web application:**

```
python manage.py runserver
```

That is all you need to get started. Follow the next steps to set up your database.


### 2. PostgreSQL

The first thing to do is make sure you have [PostgreSQL](https://www.postgresql.org/) downloaded, installed, and **running**.  Then either get [Postico](https://eggerapps.at/postico/ "PostgreSQL application for Mac") or open a `psql` shell.

**Run the following commands:**

```
CREATE USER <your_username> WITH CREATEDB;
ALTER USER <your_username> WITH PASSWORD '<your_password>';
CREATE DATABASE <your_database> WITH OWNER <your_username>;
```

Now you should have a development database setup on your local machine for the app to use.

