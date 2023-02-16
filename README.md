# API-Annuaire-Sante
Non-official SaaS providing API features for public French healthcare professionals data.

## Work in progess - not ready to be used yet

### Installation  
First ensure you have python globally installed in your computer. If not, you can get python [here](python.org).

After doing this, confirm that you have installed virtualenv globally as well. If not, run this:

    $ pip install virtualenv
Then, Git clone this repo to your PC

    $ git clone git@github.com:remaudcorentin-dev/API-Annuaire-Sante.git
    $ cd API-Annuaire-Sante
Create a virtual environment

    $ virtualenv .venv && source .venv/bin/activate
Install dependancies

    $ pip install -r requirements.txt
Make migrations & migrate

    $ python manage.py makemigrations && python manage.py migrate
Create Super user
    
    $ python manage.py createsuperuser

### Launching the app
    $ python manage.py runserver

### Run Tests
    $ python manage.py test

