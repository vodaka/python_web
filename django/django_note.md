# 1 Environment
- of course, python is needed
- virtualenv(optional ,but it is recommanded): $ sudo pip install virtualenv
- django: $ sudo pip install django 
# 2 Create a project
- $ django-admin.py startproject PROJECTNAME(e.g.,ecomstore)
- $ python manage.py runserver
# 3 Creating the MySQL Database
- mysql> CREATE DATABASE ecomstore CHARACTER SET utf8;
- mysql> CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
- mysql> GRANT ALL ON ecomstore.* TO 'username'@'localhost';

