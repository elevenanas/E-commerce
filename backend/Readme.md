To start working on it: Windows

1- clone this repo into your workdir

git clone https://github.com/elevenanas/E-commerce.git
cd E-commerce/backend

2- create virtualenv:

on windows python -m venv venv

2- activate your virtualenv (from Powershell)

venv\scripts\activate

or 2- activate your virtualenv (from git bash)

cd envname/scripts
. activate

3- upgrade pip 

python -m pip install --upgrade pip

5- Insatll all the required packages 

pip install -r requirements.txt

6- migrate the database 

python manage.py migrate

7- run the developpement server 

python manage.py runserver (by default it runs on localhost:8000)