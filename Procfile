web: gunicorn app:app --timeout 60 --max-requests 1200 --workers 3 --log-level=DEBUG
worker: python worker.py