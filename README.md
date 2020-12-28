# <img width="30" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/django.svg" />&nbsp; Django Project Boilerplate

This repository is a boilerplate Django project for quickly getting started

<a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" /></a>
<a href="https://www.djangoproject.com/"><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" /></a>


## Getting started

Steps:

1. Clone/pull/download this repository
2. Create a virtualenv with `virtualenv .venv` and install dependencies with `pip install -r requirements.txt`
3. Configure your .env variables
4. Rename your project with `python manage.py rename <yourprojectname> <newprojectname>`
5. Collect all static files `python manage.py collectstatic`

This project includes:

1. Setting up multiple settings modules
2. Use python decouple for change parameters
2. Django commands for renaming your project