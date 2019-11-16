title: Flask Dashboard Black

# [Flask Dashboard Black](https://appseed.us/admin-dashboards/flask-dashboard-black)

**[Open-Source Admin Dashboard](https://appseed.us/admin-dashboards/flask-dashboard-black)** coded in **Flask Web Framework** on top of **Black Dashboard** design, crafted by Creative-Tim agency. **Dashboard** features:

- SQLite database
- SQLAlchemy ORM
- Session-Based authentication flow (login, register)

<br />

![Flask Dashboard Black - Open-Source Admin Panel](https://raw.githubusercontent.com/app-generator/flask-black-dashboard/master/screenshots/flask-black-dashboard-intro.gif)

<br />

## Setup the environment
---

In order to use the boilerplate, we need [Python3](/what-is/python/) and `virtualenv` python library.

<br />

> *Note*: **Python2 is not supported**, the EOL of this version announced [here](https://www.python.org/doc/sunset-python-2/). In order to use our kits, please migrate to Pyhton3. Thank you!

<br />

```bash
$ # Test the Python install
$ python --version
$ Python 3.7.2
$
$ # install Virtualenv using PIP
$ pip install virtualenv
```

<br />

## Build from [sources](https://github.com/app-generator/flask-black-dashboard/)
---

```bash
$ # clone the sources
$ git clone https://github.com/app-generator/flask-black-dashboard.git
$ cd flask-black-dashboard
$
$ # install modules using a virtualenv
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # install deps
$ pip install -r requirements.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$ 
$ # Create SQLite database using the Flask console
$ flask shell
>> from app import db
>> db.create_all()
>> quit()
$ # SQLite database.db should be created in the app folder:
$ # app\database.db
$
$ flask run
$ # app is running on port 5000
```

<br />

## Project Structure
---

The boilerplate code is built with a modular structure that follows the recommended pattern used by many open-source projects. The most important files / directories are listed bellow:

- [run.py](https://github.com/app-generator/flask-black-dashboard/blob/master/run.py)
- [app /](https://github.com/app-generator/flask-black-dashboard/tree/master/app)
- [app / __init__.py](https://github.com/app-generator/flask-black-dashboard/blob/master/app/__init__.py)
- [app / forms.py](https://github.com/app-generator/flask-black-dashboard/blob/master/app/forms.py)
- [app / models.py](https://github.com/app-generator/flask-black-dashboard/blob/master/app/models.py)
- [app / views.py](https://github.com/app-generator/flask-black-dashboard/blob/master/app/views.py)

<br />

```bash
< ROOT > - Flask Dashboard Black  # application root folder
    |
    |--- app/                     # application folder  
    |--- app/__init__.py          # application constructor  
    |--- app/configuration.py     # application config  
    |--- app/forms.py             # application forms  
    |--- app/models.py            # application models  
    |--- app/views.py             # application routing
    |  
    |--- requirements.txt         # Requirements for development - SQLite storage
    |--- run.py                   # bootstrap the app
    |
    |-----------------------------
```

<br />

## Support
---

- Free support via eMail < [support @ appseed.us](https://appseed.us/support) > and [Github](https://github.com/app-generator/flask-black-dashboard/issues/)
- 24/7 Live Support via [Discord](https://discord.gg/fZC6hup) for paid plans and commercial products.

<br />

## Resources

- [Flask Dashboard Black](https://appseed.us/admin-dashboards/flask-dashboard-black) - Product page
- [Flask Dashboard Black](https://flask-black-dashboard.appseed.us/) - Live DEMO
- [Flask Dashboard Black](https://github.com/app-generator/flask-black-dashboard/) - Source code published on Github
- [Flask Framework](https://www.palletsprojects.com/p/flask/) - Offcial website
- [Flask Dashboard - Open-Source Boilerplates](https://dev.to/sm0ke/flask-dashboard-open-source-boilerplates-dkg) - A popular article published on Dev.to platform
- [Flask Dashboard](https://admin-dashboards.com/tags/flask-dashboard) - Index provided by **Admin-Dashboards.com**