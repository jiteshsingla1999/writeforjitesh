web: flask db upgrade; flask translate compile; gunicorn -b :$PORT microblog:app
release: python microblog.py db upgrade
