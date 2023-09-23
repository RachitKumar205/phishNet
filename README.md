# phishNet

# Steps to run
1. Clone this repository into desired directory.
2. Navigate to the directory using terminal.
3. Run `python -m venv ./__venv__` to initialize a virtual environment.
4. Run `pip install -r "requirments.txt"` to install all requirments.
5. Run `cd web`
6. Run `python manage.py runserver`.
7. Wait for the following to appear (datetime and version might not be the same)
```
September 23, 2023 - 09:06:58
Django version 4.2.5, using settings 'phishNet_backend.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```
8. Go to `localhost:8000/api/verify`
9. Enter URL and click submit to get safety analysis.