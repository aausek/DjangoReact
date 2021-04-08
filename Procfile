release: python manage.py migrate
web: gunicorn backend.wsgi --log-file -
PATH="/Applications/Postgres.app/Contents/Versions/latest/bin:$PATH"
