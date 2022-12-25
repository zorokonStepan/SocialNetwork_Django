    pip install django

## Настройка django-crispy-forms

[https://django-crispy-forms.readthedo..](https://django-crispy-forms.readthedo..)

    pip install django-crispy-forms

## Настройка django-cleanup

[https://github.com/un1t/django-cleanup](https://github.com/un1t/django-cleanup)

    pip install django-cleanup==6.0.0

## Настройка pillow 

    pip install pillow

## Настройка django-ckeditor 

[https://pypi.org/project/django-ckedi...](https://pypi.org/project/django-ckedi...)

    pip install django-ckeditor

## Настройка channels

[https://channels.readthedocs.io/en/st..](https://channels.readthedocs.io/en/st..)

    python -m pip install -U channels

## Настройка django-allauth

[https://django-allauth.readthedocs.io...](https://django-allauth.readthedocs.io...)
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

[https://django-braces.readthedocs.io/...](https://django-braces.readthedocs.io/...)

    pip install django-braces
    