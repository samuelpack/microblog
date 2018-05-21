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

tell flask how to import by setting the FLASK_APP env variable:
    export FLASK_APP=<filename.py>

run application:
    flask run

***

'no module named...'

remember to use 'flask shell'