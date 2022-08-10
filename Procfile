release: bash release.sh && python manage.py migrate
web: gunicorn elb_project.wsgi --log-file -