### This is a simple To-Do app built in _Python Django_ and _PostgreSQL_ for the database.
Here is the code in settings.py to connecting the model to the database:
``` python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'TodoDB',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'localhost'
    }
}
```
