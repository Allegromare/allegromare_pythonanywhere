# SETUP A DJANGO PROJECT

# Create a Githuh repository

# Clone the Github repository in a directory

# Create a virtual environment

python3 -m venv env

# Activate a virtual environment

source env/bin/activate

# Install Django

pip3 install django

NB: if you nedd a specific version of Django (in my example 4.2.2) write:
pip3 install django==4.2.2

# Save packages installed and their version in a file

pip freeze > requirements.txt

# Create a Django project

django-admin startproject django_website
