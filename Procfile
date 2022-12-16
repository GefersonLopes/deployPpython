web: python manage.py collectstartic --no-input \
    && python manage.py migrate
    && gunicorn bandkamp.wsgi --log-level debug