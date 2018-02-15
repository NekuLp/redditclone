web: gunicorn config.wsgi:application
worker: celery worker --app=reddit.taskapp --loglevel=info
