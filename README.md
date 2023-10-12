# mysite - Django Project with Reusable Polls App

## Introduction
This is a Django project named "mysite" that includes a reusable app called "polls." The "polls" app is created using `setuptools`, making it easy to include in other Django projects.

## Installation
To get started with this project, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/subarnasaikia/django-polls.git
```
2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
```


3. Install the project dependencies:

```bash
pip install -r requirements.txt
```

4. Apply database migrations:

```bash
python manage.py migrate
```

5. Run the development server:

```bash
python manage.py runserver
```



The Django project "mysite" should now be up and running at [http://127.0.0.1:8000/](http://127.0.0.1:8000/). You can access the "polls" app at [http://127.0.0.1:8000/polls/](http://127.0.0.1:8000/polls/).




