# start_django_app

## Solving `command not found: pipenv` ==> (pip install pipenv)
---
## ERROR: Could not install packages due to an OSError: [WinError 2] The system can
 - not find the file specified: 'C:\\Python310\\Scripts\\virtualenv.exe' -> 'C:\\Py
thon310\\Scripts\\virtualenv.exe.deleteme'
- ===> pip install pipenv --user
---
- this command to find where install python on your pc:
  - (python -c "import os, sys; print(os.path.dirname(sys.executable))")

---
- bash: sudo: command not found ==>>(pip3 install sudo)
if not working  try to run git bash as admin then try to insatll it by 
  - chocolatey by this command (choco install sudo)

---
- ==>(sudo pip3 install django)
  to force terminal to install django 
- ==>(django --version) to check which version and if is installed.
---
- ==>(pipenv shell) to activate virtual env to use python interpreter inside 
this venv
- ==>(django-admin startproject mysite) to create the django's project
- ==>(python manage.py runserver) to run the server by default on port 8000.
- ==>(python manage.py runserver 8080) to run server on port 8080
- ==>(ctrl+c) to terminate the server.
- ==>(python manage.py migrate) to apply all migrations for app.

---
- P.s: pipfile is like package.json for js projects so in this file we can see 
all required packages to run this app.
---
