# Project Structure
```
├── Web Application/
    ├── 1. Getting Started with Django/
    │   ├── making_pages/
    │   │   ├── ll_project/
    │   │   │   ├── __init__.py
    │   │   │   ├── asgi.py
    │   │   │   ├── wsgi.py
    │   │   │   └── urls.py
    │   │   ├── learning_logs/
    │   │   │   ├── __init__.py
    │   │   │   ├── migrations/
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── 0001_initial.py
    │   │   │   │   └── 0002_entry.py
    │   │   │   ├── tests.py
    │   │   │   ├── admin.py
    │   │   │   ├── templates/
    │   │   │   │   └── learning_logs/
    │   │   │   │       └── index.html
    │   │   │   ├── apps.py
    │   │   │   ├── views.py
    │   │   │   ├── urls.py
    │   │   │   └── models.py
    │   │   └── manage.py
    │   ├── setting_up_project/
    │   │   ├── ll_project/
    │   │   │   ├── __init__.py
    │   │   │   ├── asgi.py
    │   │   │   ├── wsgi.py
    │   │   │   └── urls.py
    │   │   └── manage.py
    │   ├── starting_an_app/
    │   │   ├── learning_logs/
    │   │   │   ├── __init__.py
    │   │   │   ├── migrations/
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── 0001_initial.py
    │   │   │   │   └── 0002_entry.py
    │   │   │   ├── tests.py
    │   │   │   ├── views.py
    │   │   │   ├── admin.py
    │   │   │   ├── apps.py
    │   │   │   └── models.py
    │   │   ├── ll_project/
    │   │   │   ├── __init__.py
    │   │   │   ├── asgi.py
    │   │   │   ├── wsgi.py
    │   │   │   └── urls.py
    │   │   └── manage.py
    │   └── building_additional_pages/
    │       ├── learning_logs/
    │       │   ├── __init__.py
    │       │   ├── migrations/
    │       │   │   ├── __init__.py
    │       │   │   ├── 0001_initial.py
    │       │   │   └── 0002_entry.py
    │       │   ├── tests.py
    │       │   ├── admin.py
    │       │   ├── apps.py
    │       │   ├── templates/
    │       │   │   └── learning_logs/
    │       │   │       ├── base.html
    │       │   │       ├── index.html
    │       │   │       ├── topics.html
    │       │   │       └── topic.html
    │       │   ├── urls.py
    │       │   ├── views.py
    │       │   └── models.py
    │       ├── ll_project/
    │       │   ├── __init__.py
    │       │   ├── asgi.py
    │       │   ├── wsgi.py
    │       │   └── urls.py
    │       └── manage.py
    ├── 2. User Accounts/ (11600 tokens)
    │   ├── setting_up_user_accounts/ (4200 tokens)
    │   │   ├── accounts/ (1100 tokens)
    │   │   │   ├── __init__.py
    │   │   │   ├── migrations/ (100 tokens)
    │   │   │   │   └── __init__.py
    │   │   │   ├── models.py
    │   │   │   ├── tests.py
    │   │   │   ├── admin.py
    │   │   │   ├── apps.py
    │   │   │   ├── templates/ (200 tokens)
    │   │   │   │   └── registration/ (200 tokens)
    │   │   │   │   │   ├── register.html
    │   │   │   │   │   └── login.html
    │   │   │   ├── urls.py
    │   │   │   └── views.py (200 tokens)
    │   │   ├── learning_logs/ (2400 tokens)
    │   │   │   ├── __init__.py
    │   │   │   ├── migrations/ (500 tokens)
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── 0001_initial.py (200 tokens)
    │   │   │   │   └── 0002_entry.py (200 tokens)
    │   │   │   ├── tests.py
    │   │   │   ├── admin.py
    │   │   │   ├── apps.py
    │   │   │   ├── templates/ (1000 tokens)
    │   │   │   │   └── learning_logs/ (1000 tokens)
    │   │   │   │   │   ├── index.html
    │   │   │   │   │   ├── new_topic.html
    │   │   │   │   │   ├── new_entry.html
    │   │   │   │   │   ├── edit_entry.html
    │   │   │   │   │   ├── topics.html (200 tokens)
    │   │   │   │   │   ├── base.html (200 tokens)
    │   │   │   │   │   └── topic.html (200 tokens)
    │   │   │   ├── forms.py
    │   │   │   ├── urls.py (200 tokens)
    │   │   │   └── models.py (200 tokens)
    │   │   ├── ll_project/ (500 tokens)
    │   │   │   ├── __init__.py
    │   │   │   ├── asgi.py
    │   │   │   ├── wsgi.py
    │   │   │   └── urls.py (200 tokens)
    │   │   └── manage.py (200 tokens)
    │   ├── allowing_users_to_enter_data/ (3000 tokens)
    │   │   ├── learning_logs/ (2300 tokens)
    │   │   │   ├── __init__.py
    │   │   │   ├── migrations/ (500 tokens)
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── 0001_initial.py (200 tokens)
    │   │   │   │   └── 0002_entry.py (200 tokens)
    │   │   │   ├── tests.py
    │   │   │   ├── admin.py
    │   │   │   ├── apps.py
    │   │   │   ├── templates/ (900 tokens)
    │   │   │   │   └── learning_logs/ (900 tokens)
    │   │   │   │   │   ├── base.html
    │   │   │   │   │   ├── index.html
    │   │   │   │   │   ├── new_topic.html
    │   │   │   │   │   ├── new_entry.html
    │   │   │   │   │   ├── edit_entry.html
    │   │   │   │   │   ├── topics.html (200 tokens)
    │   │   │   │   │   └── topic.html (200 tokens)
    │   │   │   ├── forms.py
    │   │   │   ├── urls.py (200 tokens)
    │   │   │   └── models.py (200 tokens)
    │   │   ├── ll_project/ (500 tokens)
    │   │   │   ├── __init__.py
    │   │   │   ├── asgi.py
    │   │   │   ├── wsgi.py
    │   │   │   └── urls.py (200 tokens)
    │   │   └── manage.py (200 tokens)
    │   └── allowing_users_to_own_their_data/ (4400 tokens)
    │   │   ├── accounts/ (1100 tokens)
    │   │       ├── __init__.py
    │   │       ├── migrations/ (100 tokens)
    │   │       │   └── __init__.py
    │   │       ├── models.py
    │   │       ├── admin.py
    │   │       ├── tests.py
    │   │       ├── apps.py
    │   │       ├── templates/ (200 tokens)
    │   │       │   └── registration/ (200 tokens)
    │   │       │   │   ├── register.html
    │   │       │   │   └── login.html
    │   │       ├── urls.py
    │   │       └── views.py (200 tokens)
    │   │   ├── ll_project/ (500 tokens)
    │   │       ├── __init__.py
    │   │       ├── asgi.py
    │   │       ├── wsgi.py
    │   │       └── urls.py (200 tokens)
    │   │   ├── learning_logs/ (2600 tokens)
    │   │       ├── __init__.py
    │   │       ├── migrations/ (700 tokens)
    │   │       │   ├── __init__.py
    │   │       │   ├── 0001_initial.py (200 tokens)
    │   │       │   ├── 0003_topic_owner.py (200 tokens)
    │   │       │   └── 0002_entry.py (200 tokens)
    │   │       ├── tests.py
    │   │       ├── admin.py
    │   │       ├── apps.py
    │   │       ├── templates/ (1000 tokens)
    │   │       │   └── learning_logs/ (1000 tokens)
    │   │       │   │   ├── index.html
    │   │       │   │   ├── new_topic.html
    │   │       │   │   ├── new_entry.html
    │   │       │   │   ├── edit_entry.html
    │   │       │   │   ├── topics.html (200 tokens)
    │   │       │   │   ├── base.html (200 tokens)
    │   │       │   │   └── topic.html (200 tokens)
    │   │       ├── forms.py
    │   │       ├── urls.py (200 tokens)
    │   │       └── models.py (200 tokens)
    │   │   └── manage.py (200 tokens)

    └── 3. Styling and Deploying an App/ (9900 tokens)
    │   ├── deploying_learning_log/ (5600 tokens)
    │       ├── accounts/ (1100 tokens)
    │       │   ├── __init__.py
    │       │   ├── migrations/ (100 tokens)
    │       │   │   └── __init__.py
    │       │   ├── models.py
    │       │   ├── admin.py
    │       │   ├── tests.py
    │       │   ├── apps.py
    │       │   ├── templates/ (200 tokens)
    │       │   │   └── registration/ (200 tokens)
    │       │   │   │   ├── register.html
    │       │   │   │   └── login.html
    │       │   ├── urls.py
    │       │   └── views.py (200 tokens)
    │       ├── ll_project/ (500 tokens)
    │       │   ├── __init__.py
    │       │   ├── asgi.py
    │       │   ├── wsgi.py
    │       │   └── urls.py (200 tokens)
    │       ├── learning_logs/ (2500 tokens)
    │       │   ├── __init__.py
    │       │   ├── migrations/ (700 tokens)
    │       │   │   ├── __init__.py
    │       │   │   ├── 0001_initial.py (200 tokens)
    │       │   │   ├── 0003_topic_owner.py (200 tokens)
    │       │   │   └── 0002_entry.py (200 tokens)
    │       │   ├── tests.py
    │       │   ├── admin.py
    │       │   ├── apps.py
    │       │   ├── templates/ (900 tokens)
    │       │   │   └── learning_logs/ (900 tokens)
    │       │   │   │   ├── new_topic.html
    │       │   │   │   ├── new_entry.html
    │       │   │   │   ├── edit_entry.html
    │       │   │   │   ├── index.html (200 tokens)
    │       │   │   │   ├── topics.html (200 tokens)
    │       │   │   │   └── topic.html (200 tokens)
    │       │   ├── forms.py
    │       │   ├── urls.py (200 tokens)
    │       │   └── models.py (200 tokens)
    │       ├── .platform/ (500 tokens)
    │       │   ├── local/ (300 tokens)
    │       │   │   ├── .gitignore
    │       │   │   ├── project.yaml
    │       │   │   └── README.txt
    │       │   ├── services.yaml
    │       │   └── routes.yaml
    │       ├── .gitignore
    │       ├── requirements_remote.txt
    │       ├── templates/ (200 tokens)
    │       │   ├── 500.html
    │       │   └── 404.html
    │       ├── requirements.txt
    │       ├── manage.py (200 tokens)
    │       └── .platform.app.yaml (300 tokens)
    │   └── styling_learning_log/ (4300 tokens)
    │       ├── accounts/ (1100 tokens)
    │           ├── __init__.py
    │           ├── migrations/ (100 tokens)
    │           │   └── __init__.py
    │           ├── models.py
    │           ├── tests.py
    │           ├── admin.py
    │           ├── apps.py
    │           ├── templates/ (200 tokens)
    │           │   └── registration/ (200 tokens)
    │           │   │   ├── register.html
    │           │   │   └── login.html
    │           ├── urls.py
    │           └── views.py (200 tokens)
    │       ├── ll_project/ (500 tokens)
    │           ├── __init__.py
    │           ├── asgi.py
    │           ├── wsgi.py
    │           └── urls.py (200 tokens)
    │       ├── learning_logs/ (2500 tokens)
    │           ├── __init__.py
    │           ├── migrations/ (700 tokens)
    │           │   ├── __init__.py
    │           │   ├── 0001_initial.py (200 tokens)
    │           │   ├── 0003_topic_owner.py (200 tokens)
    │           │   └── 0002_entry.py (200 tokens)
    │           ├── tests.py
    │           ├── admin.py
    │           ├── apps.py
    │           ├── templates/ (900 tokens)
    │           │   └── learning_logs/ (900 tokens)
    │           │   │   ├── new_topic.html
    │           │   │   ├── new_entry.html
    │           │   │   ├── edit_entry.html
    │           │   │   ├── index.html (200 tokens)
    │           │   │   ├── topics.html (200 tokens)
    │           │   │   └── topic.html 
    │           ├── forms.py
    │           ├── urls.py 
    │           └── models.py 
    │       └── manage.py (200 tokens)
