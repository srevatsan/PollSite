# PollSite
Demo Poll application using Django

## MySQL 5.6

You can use Homebrew to install MySQL, or do it manually:

```
% brew install mysql

```

## pip3.4

Install pip3.4 to ensure python3.4 is installed

```
% easy_install-3.4 pip

```


## Install Django and other library requirements


```
% pip3.4 install -r requirements.txt
```



## create database in MySQL
```
% create database jabba;
% show databases;
% create user 'readwrite'@'localhost' identified by 'readwrite';
% grant all privileges on polls.* to 'readwrite'@'localhost' identified by 'readwrite';
% flush privileges;
% quit;

```

## update settings.py to the correct mysql end point and configurations



## creating the data models
```
% python3.4 manage.py makemigrations
% python3.4 manage.py migrate
```

## start the polls server

Start the server in localhost:8080

```
% python3.4 manage.py runserver
```

## create a new admin super user

```
python3.4 manage.py createsuperuser
```


