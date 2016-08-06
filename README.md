# django-webpack-pack
A start pack for django with webpack

## Requirement
Python
pip
nodejs
virtualenv

## Setup
(activate a virtual environment, maybe `source ./path-to-your-venv/bin/activate` or `workon [your-venvv-name]`, if don't have, create one)
> npm i     (would also install bower and pip modules)
> echo [port number] > port
> ./manage.py migrate

## Commands

### webpack watch and build
> npm start

### django server
> npm run server

### webpack build once and exit
> npm run build

## Lints

### django-lint
> npm run lint:djg

### ls-lint
> npm run lint:ls

### pylint
> npm run lint:py

### stylint
> npm run lint:styl
