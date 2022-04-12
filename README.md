# backend

# Setup Project using virtualenv

# create folder and change folder
mkdir folder_name
cd folder_name

# The first thing to do is to clone the repository:

git clone https://github.com/PythonDeveloperVipul/django_custom_user.git
cd django_custom_user

# Create a virtual environment to install dependencies in and activate it:

python -m venv env
source env/bin/activate

# Then install the dependencies:

pip install -r requirements.txt

# Then migrate database 

python manage.py migrate

# Then runserver

python manage.py runserver