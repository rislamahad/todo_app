## This is a simple To-Do app built in =Python Django= and =PostgreSQL= for the database.
Here is the code in settings.py to connect the model to the database:
```
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
