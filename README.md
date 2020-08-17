# penntracer
A contact tracer for students living off campus at the University of Pennsylvania

# Setup

## Web App

Prerequisites: [npm](https://nodejs.org/en/), [yarn](https://classic.yarnpkg.com/en/docs/install/#mac-stable)

```
cd web
yarn 
```

## Server

Prerequisites: python 3.8

```
cd server
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```
# Running

## Web App

```
cd web
yarn start
```

### Server

```
cd server
source env/bin/activate
python manage.py runserver
```
