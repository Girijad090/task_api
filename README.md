# task_api
Instructions

⏺ Clone the repository

⏺ Install the requirements.txt (In a virtual environment preferably) for that in task_api Directory type command as

virtualenv env

⏺ Activate the virtual environment by

source env/Scripts/activate

cd api

pip install -r requirements.txt


python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

Username: Jerry
Email address:jerry@gmail.com
password: Jerry
Password (again):Jerry

⏺ Run the application

python manage.py runserver

Go to localhost:8000 click on "contactapi": "http://localhost:8000/contactapi/"

⏺Add the fills
and enjoy!😊

⏺For delete and update add id number in browser url.

⏺Example:
You have: http://localhost:8000/contactapi/
New one : http://localhost:8000/contactapi/1

