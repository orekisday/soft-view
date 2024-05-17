## create and activate a virtual environment using
- (Mac) python3 -m venv [invironment name]
- source [invironment name]/bin/activate
## run the command below to get all the packages
- pip install -r requirements.txt
## create a super user and run the server
- python manage.py createsuperuser
- python manage.py runserver
- ## make migrations and migrate the changes
- python manage.py makemigrations
- python manage.py migrate
# Follow the steps from the terminal
