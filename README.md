# D7.8
pip install -r requirements.txt<br>
python manage.py runserver>br>

http://127.0.0.1:8000/<br>
http://127.0.0.1:8000/admin<br>
http://127.0.0.1:8000/admin/socialaccount/socialaccount/2/change/<br>
Пароль от админки:<br>
admin<br>
123456<br>
В качестве домашнего задания нужно добавить создание пользователей в качестве моделей, для которых нужно использовать встроенные модели Django (django.contrib.auth.models.User), а их профили должны либо создаваться отдельной (самодельной) формой, либо при помощи allauth с авторизацией через github. В любом случае, объекты профилей должны быть экземплярами SocialAccount (allauth). Любая дополнительная информация должна сохраняться в виде словаря (JSON) в поле extra_data.
