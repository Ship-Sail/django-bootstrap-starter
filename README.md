# Django Bootstrap Starter

This is a starter template to pre-install an app within a new django project that has a customizable version of
bootstrap and font-awesome.

## Steps to use this template
- Create a directory for your project and name it whatever you want
- Start a python venv inside of it
- Install django `pip install django`
- Decide on your new Django project name (this will replace `project_name` throughout the project)
- Run `django-admin startproject --template https://github.com/Ship-Sail/django-bootstrap-starter/archive/main.zip <your_new_django_project_name> .`
- Run `pip install -r requirements.txt`. This will install other dependencies needed despite already installing django do you could run the startproject command
- `cd app && npm install`
- `npm run sass:build` to build scss into appropriate css for templates to use
- `npm run sass:watch` to watch sass files for changes
- Create a `.env` file and make sure to populate `SECRET_KEY` with your generated key
