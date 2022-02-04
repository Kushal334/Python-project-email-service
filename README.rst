============
Installation
============

--------------
Pre-Requisites
--------------
* `Pycharm`
* `Python3.9`
* `SQLite Studio Server`


Installing the Project
::
Create the virtual environments using python -m venv environment_name
Install the required packages mentioned in the requirements folder pip install -r requirements/requirements.txt


Django Specific configurations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Populate DB using below commands:
    a. python manage.py makemigrations
    b. python manage.py migrate
2. Start server using below command:
    a. python manage.py runserver

----------------
Create Sendgrid account
----------------

1. Create a free send grid account
2. Generate the API key and template for sending the mail
3. For security purposes use the decouple to keep the credentials

Important Note:
~~~~~~~~~~~~~~~

    1. To avoid commit python compiled files(.pyc) files please add these into .gitignore file \*.pyc
    2. Before commit the code please use pep8 check. please refer below url:
        https://www.python.org/dev/peps/pep-0008/
            we can use PyCharm(editor) Code -> Inspect Code utility for pep8 guideline.

-------------------------
Code Style Check
-------------------------
    We used pycodestyle for Pep8 code style checker.Give below command to run:

    a.pycodestyle

    We can also run pycoestyle for one file using below command:

    b. pycodestyle file name



