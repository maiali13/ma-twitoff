# ma-twitoff

## Setup

Migrate the db:

```sh
FLASK_APP=web_app flask db init
FLASK_APP=web_app flask db migrate
FLASK_APP=web_app flask db upgrade
```

## Usage

```sh
# Mac:
FLASK_APP=app.py flask run

# Windows:
set FLASK_APP=app.py # one-time thing, to set the env var
flask run
```
