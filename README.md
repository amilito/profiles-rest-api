# Profiles REST API

Profiles REST API course code

vagrant init ubuntu/bionic64
vagrant up
vagrant ssh - start conn to server
exit - exit connection
-------------------------------------------
python hello_world.py

cd /vagrant/
python -m venv ~/env - new env inside vm
source ~/env/bin/activate 
deactivate
 
pip install -r requirements.txt
-------------------------------------------
create project
django-admin.py startproject profiles_project .

create app
python manage.py startapp profiles_api


python manage.py runserver 0.0.0.0:8000
type in chrome 127.0.0.1:8000

------------------------------------------
after model creation
python manage.py makemigrations profiles_api