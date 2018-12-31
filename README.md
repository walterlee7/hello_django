Django Project with Python 3 for VS Code

macOS installation instructions
1. create a project folder
2. create virtual environment with terminal: python3 -m venv env
3. in VS Code, use Python: Select Interpreter to choose Python version
4. activate Django environment with in terminal: source env/bin/activate
5. terminal: python -m pip install django

Django app creation
1. create project in terminal: django-admin startproject web_project .
2. verify virtual environment in terminal: python manage.py runserver
3. terminal: python manage.py startapp hello
4. hello/views.py: used for single view
5. hello/urls.py: used for specifying URL routes
6. web_project/urls.py: used for handling URL routing
7. run program: terminal: python manage.py runserver

Django Debugging in VS Code
1. turn on Debug View
2. change no Configuration to Python (creates a launch.json)
3. change Python configuration to Python: Django
4. click Play button to run server with Debugging make sure that the port is not in use