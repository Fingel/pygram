# pygram
An instagram clone

[Get python3](https://www.python.org)

[Django](https://www.djangoproject.com)

## Installation

Pygram requires a working installation of Python 3.

Once you have python installed, create a new virtualenv:

    python3 -m venv new env
    source env/bin/activate

Now that you have the virtualenv activated, you can install the requirements:

    pip install -r requirements.txt

Set up the database:

    ./manage.py migrate

Run a development server:

    ./manage.py runserver

Create a user to login to the /admin/ site:

    ./manage.py createsuperuser
