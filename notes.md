NOTES:

create virtual env:
    python3 -m venv venv


activate virtual env:
    source venv/bin/activate

install Flask (and extensions) into virtual env:
    pip install Flask
    pip install flask-wtf
    pip install flask-sqlalchemy
    pip install flask-migrate
    pip install flask-login
    pip install flask-mail
    pip install pyjwt
    pip install flask-bootstrap
    pip install flask-moment
    pip install flask-babel

tell flask how to import by setting the FLASK_APP env variable:
    export FLASK_APP=<filename.py>

run application:
    flask run

***

'no module named...'

remember to use 'flask shell'

when you are developing your app, you can use debug mode, like so:

    export FLASK_DEBUG=1

run a dummy email server in a second terminal session :

    (venv) $ python -m smtpd -n -c DebuggingServer localhost:8025

***

to make a multi line comment, use triple quotes -> ''' comment '''


### add an alert so that people dont think you can speak spanish ###