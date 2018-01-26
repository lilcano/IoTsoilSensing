web: gunicorn config.wsgi:application
worker: celery worker --app=soil.taskapp --loglevel=info
