# Django Create Project
 run this command in the command prompt:

```bash
  django-admin startproject weather_app
```

Django creates a weather_app folder on my computer, with this content:

```bash
  weather_app
    manage.py
    weather_app/
        __init__.py
        asgi.py
        settings.py
        urls.py
        wsgi.py
```

## Run the Django Project

Navigate to the /weather_app folder and execute this command in the command prompt:

```bash
py manage.py runserver
```  

Which will produce this result:



```bash
You have 18 unapplied migration(s). 
Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
February 18, 2023 - 14:24:21
Django version 4.1.7, using settings 'weather_app.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```
Open a new browser window and type 127.0.0.1:8000 in the address bar.

