# Flasktutorial

> Implement basic CRUD operation in flask

## How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv .venv
```

3. Then run the command:
```
$ source .venv/bin/activate
```

4. Then install the dependencies:
```
$ (.venv) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (.venv) python app.py
```

This server will start on port 5000 by default.

## How To Deploy
1. Login `heroku`:
```
$ heroku login
```
2. Create `heroku` app:
```
$ heroku create CUSTOM-APP-NAME
```
3. Push the Git repository to this remote to trigger the building and deployment process
```
$ git push heroku main
```

Demo Link: https://flasktutorial-20012025-cfee3b8505e8.herokuapp.com/
