# Drink Management API with Django Rest Framework

This is a tutorial project for creating a simple Drink Management API using Django and Django Rest Framework (DRF). This API allows you to create, read, update, and delete drinks with fields for the drink's name and description.

## Requirements

- Python 3.7+
- Django 3.0+
- Django Rest Framework 3.11+

## Setup

### 1. Clone the Repository
```
git clone https://github.com/yourusername/drink-management-api.git
cd drink-management-api
```

### 2. Create a Virtual Environment and Activate It
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```
pip install -r requirements.txt
```

### 4. Apply Migrations
```
python manage.py migrate
```

### 5. Create a Superuser (for accessing the admin site)
```
python manage.py createsuperuser
```

### 6. Run the Development Server
```
python manage.py runserver
```
