# Packages
- Django
- Django-RestFramework
- Python-dotenv


for creating secret keys in python shell:

    from django.core.management.utils import get_random_secret_key
    
    print(get_random_secret_key())
