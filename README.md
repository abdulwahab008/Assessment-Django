1.Install the python 

2.Open the command prompt and run these commands

3.pip install django mysqlclient

4.pip install django-crispy-forms

5.pip install crispy-bootstrap4

6.Now next create the mysql database check the youtube tutorial to setup the mysql

7.After settingup of mysql

8.Write these commands on mysql

9.CREATE DATABASE mydatabase;

10.CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'pakistan';

11.GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';

12.FLUSH PRIVILEGES;

After creation again go to CMD and run these commands 

13.python manage.py makemigrations

14.python manage.py migrate

15.python manage.py runserver             //this will run the server

16.Now open browser and write this ip it will open your Webpage http://127.0.0.1:8000/accounts/signup/

17.If you want to login then http://127.0.0.1:8000/accounts/login/
