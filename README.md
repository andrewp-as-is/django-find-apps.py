<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-find-apps.svg?maxAge=3600)](https://pypi.org/project/django-find-apps/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-find-apps.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-find-apps.py/actions)

### Installation
```bash
$ [sudo] pip install django-find-apps
```

#### Examples
`settings.py`
```python
import django_find_apps

INSTALLED_APPS = django_find_apps.find_apps(".")
```

```
apps
├── app1
|   ├── __init__.py
|   └── models.py
├── app2
|   ├── __init__.py
|   └── templatetags
└── app3
    ├── __init__.py
    └── management
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
