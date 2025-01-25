Installation
- git clone git@github.com:ripan/flasktutorial.git
- cd flasktutorial
- pip install virtualenv
- virtualenv .venv
- source .venv/bin/activate
- pip install gunicorn
- pip install Flask-SQLAlchemy
- pip install flask
- pip freeze > requirements.txt

Run
- flask run --debug
