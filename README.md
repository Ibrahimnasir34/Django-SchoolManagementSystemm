python -m venv env
 env\Scripts\activate


 pip install -r requirements.txt

//you may want to delete the db.sqlite file  if you want to delete old data
python manage.py migrate

python manage.py createsuperuser

python manage.py runserver





