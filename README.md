# Simple Blog

Simple Django 2.1 Blog Implementation

# Setup

- Create a virtual environment
- Activate the environment
- Pull the code
- Install the required packages
	> `pip install -r` [requirements.txt](requirements.txt)
- Setup PostgreSQL db and update db details to the [setting.py](settings.py) file(change to any other db as per preference 
- `python manage.py makemigrations polls`
- `python manage.py migrate`
- `python manage.py runserver`
	
### If you wish to access the admin panel
- Create a superuser
	> `python manage.py createsuperuser`