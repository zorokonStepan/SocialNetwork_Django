## Настройка django-crispy-forms

[https://docs.djangoproject.com/en/4.1/](https://docs.djangoproject.com/en/4.1/)

    pip install django

## Настройка django-crispy-forms

[https://django-crispy-forms.readthedocs.io/en/latest/](https://django-crispy-forms.readthedocs.io/en/latest/)

    pip install django-crispy-forms

## Настройка django-cleanup

[https://github.com/un1t/django-cleanup](https://github.com/un1t/django-cleanup)

    pip install django-cleanup==6.0.0

## Настройка pillow 

[https://pypi.org/project/Pillow/](https://pypi.org/project/Pillow/)

    pip install pillow

## Настройка django-ckeditor 

[https://pypi.org/project/django-ckeditor/](https://pypi.org/project/django-ckeditor/)

    pip install django-ckeditor

## Настройка channels

[https://channels.readthedocs.io/en/stable/](https://channels.readthedocs.io/en/stable/)

    python -m pip install -U channels

## Настройка django-allauth

[https://django-allauth.readthedocs.io/en/latest/](https://django-allauth.readthedocs.io/en/latest/)
    .
    pip install django-allauth

## Настройка dotenv

[https://pypi.org/project/python-dotenv/](https://pypi.org/project/python-dotenv/)

    pip install python-dotenv

```python


import os

from pathlib import Path
from dotenv import load_dotenv
from django.contrib.messages import constants as messages

# Loading ENV
env_path = Path('.') / '.env'

# env_path = '.test.env'
load_dotenv(dotenv_path=env_path)
```

## Настройка django-braces

[https://django-braces.readthedocs.io/en/latest/](https://django-braces.readthedocs.io/en/latest/)

    pip install django-braces
    