# django-webpack-pack
A start pack for django with webpack

## Requirement
- Python3
- pip
- nodejs
- virtualenv

## Setup

### Create a virtual environment
```
$ virtualenv ~/.virtualenvs/[your-venv-name]/ -p python3
```

### Activate virtual environment
```
$ source ~/.virtualenvs/[you-venv-name]/bin/activate
```

### Install dependencies
```
$ npm i     (would also install pip modules)
```

### Set the port number at which django dev server will run
```
$ echo [port number] > port
```

### Migrate database
```
$ ./manage.py migrate
```

## Commands

### webpack watch and build
```
$ npm start
```

### django server
```
$ npm run django
```

### webpack build once and exit
```
$ npm run build
```

## Lints

### django-lint
```
$ npm run lint:djg
```

### ls-lint
```
$ npm run lint:ls
```

### pylint
```
$ npm run lint:py
```

### stylint
```
$ npm run lint:styl
```
