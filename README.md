What is Django?
  -> A high-level python web framework that encourages rapid development and clean, pragmatic design.
  -> follow the MTV(Model-Templete-View) architectural pattern.

Install Django:
  cmd ' pip install django '

1. To create Django Project folder:
  in cmd ' django-admin startproject <project_name> '
  cd <project_name>

2. project Structure:
<project_name>/
  <project_name>/
    __init__.py
    asgi.py
    settings.py
    urls.py
    wsgi.py
  manage.py
  db.sqlite3

3. Run developmet server:
   python manage.py runserver
