# djangomodels
python -m venv myenv
cd myenv
.\scripts\activate
python –version
pip install Django
django-admin startproject practice
cd practice
python manage.py runserver
django-admin startapp myapp

python manage.py makemigrations
python manage.py sqlmigrate myapp 0001
python manage.py migrate


python manage.py createsuperuser
