# hello-world
A flask/bootstrap implementation of an empty app ready to deploy on heroku

Fork or clone and make your own app

You will need to add a set of environment variables, e.g.:

```
ASSETS_AUTO_BUILD=True
CLEARDB_DATABASE_URL='xxx'
FLASK_APP=app.py
FLASK_DEBUG=1
FLASK_ENV=development
SECRET_KEY=secret_key
SESSION_TIMEOUT=60
SQLALCHEMY_DATABASE_URI='xxx'
STATIC_FOLDER=static
TEMPLATES_FOLDER=templates
TUNNEL_TIMEOUT=None
USE_SSL=False
WHEREAMI=HEROKU
```

You will also need to add the nodejs buildpack ``heroku buildpacks:add --index 1 heroku/nodejs -a endothermic``
