# Django Storefront

A Django web application for an e-commerce storefront.

## Features

- Product browsing and management
- Django Debug Toolbar for development
- Templating with Django's template language

## Setup

1. Clone the repository
```bash
git clone https://github.com/hmrafid/django-storefront.git
cd django-storefront
```

2. Create a virtual environment and install dependencies
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Run migrations
```bash
python manage.py migrate
```

4. Start the development server
```bash
python manage.py runserver
```

5. Visit http://127.0.0.1:8000/playground/hello/ in your browser

## Development

- Debug toolbar is available at the right side of the page when DEBUG=True
- Set breakpoints and use Django debugging with VS Code as configured in launch.json 