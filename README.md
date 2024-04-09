# Django Bootstrap Starter

This is a starter template to pre-install an app within a new django project that has a customizable version of
bootstrap and font-awesome.

## Steps to use this template
- Decide on your new Django project name (this will replace `project_name` throughout the project)
- Run `django-admin startproject --template https://github.com/Ship-Sail/django-bootstrap-starter/archive/main.zip <new_django_project_name> .`
- `cd app && npm install`
- `npm run sass:build` to build scss into appropriate css for templates to use
- `npm run sass:watch` to watch sass files for changes
