# calendar
This repository is basic DRF based project. This basically involves users creating new slots and other users can book their appointment slots

Setup Instructions :

(1) Navigate into the choice of your directory and clone the project.

(2) After Cloning, make a virtual Environment for the project using :

py -m venv env

# After Creation of virutal environment activate it.
.\env\Scripts\activate
# Or you can directly add virtual as the python Interpretor in PyCharm.
(3) After this add django and djangorestframework using :

pip3 install django
pip3 install djangorestframework
(4) After installing django and djangorestframework, move into th project directory.

# Run Migrations
py manage.py makemigrations 
py manange.py migrate
(5) Finally, create a superuser using :

py manage.py createsuperuser
(6) After creation of superuser, run :

py manage.py runserver
Thank You!
