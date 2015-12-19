web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=text_insight.taskapp --loglevel=info
