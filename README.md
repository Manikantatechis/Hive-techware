## Hive Techware
```
Hive Techware project backend built in Django API.
```

## Live Demo

**This App uses a free plan, so I am afraid that it takes time to load the pages.**

Check out [API LIVE DEMO]() here!!

## Tech used
```
* Backend : Django, Django Rest Framework, cloudinary
```

## How to Install

1. Git Clone

```
git clone -b backend https://github.com/Manikantatechis/Hive-techware
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```
