virtualenv env
cd env
cd Scripts 
activate
pip install django
pip install Pillow
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
"# WebComic" 
