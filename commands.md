# Packages

Django==4.2
djangorestframework==3.14.0
pytest==7.3.1
python-dotenv==1.0.0
Pillow==9.5.0

# Commands

from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())