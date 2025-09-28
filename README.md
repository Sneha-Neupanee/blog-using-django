# MyBlog (Django)

A full-featured blog built with Django:
- Posts with slugs
- Categories
- Comments
- Auth: signup, login, logout
- Create Post (for logged-in users)
- Search and pagination
- Bootstrap styling

## Quickstart

```bash
python -m venv venv
# Windows PowerShell
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt

python manage.py migrate 
python manage.py loaddata blog/fixtures.json  # load sample categories
python manage.py createsuperuser  # create admin
python manage.py runserver
```

Visit:
- http://127.0.0.1:8000/  (home)
- /signup/ to make an account
- /login/ to log in
- /create/ to create a post
- /admin/ to manage content
```

## Notes
- SECRET_KEY is a dev placeholder; change it for production.
- DB is SQLite (db.sqlite3). No config needed.
