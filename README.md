# Polls
Polls is a Django app to conduct web-based polls. For each question,
visitors can choose between a fixed number of answers.

## Requirements

To run this files makes sure Python and Python-Django installed first. To install Django use following command.

``pip install django`` OR  ``pip install -r requirements.txt``

## Quick Start

1. Run ``python manage.py migrate`` to create the polls models.

2. Run this files using ``python manage.py runserver`` command.

3. Make admin using ``python manage.py createsuperuser`` command and provide username, 
   email and password.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.