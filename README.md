# pet_crm project

python manage.py startapp crm_api

# миграции
python manage.py makemigrations
python manage.py migrate

что бы создать новую БД в консоли пишем:

**createdb crm_db**

удалить БД в консоли пишем:

**dropdb crm_db**

#админка

создание суперпользователя:

**python manage.py createsuperuser**