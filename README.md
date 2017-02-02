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
$ yarn (or npm i)
$ pip install -r requirements.txt
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
$ yarn start (or npm start)
```

### django server
```
$ yarn run django (or npm run django)
```

### webpack build once and exit
```
$ yarn run build (or npm run build)
```

## Lints

### django-lint
```
$ yarn run lint:djg (or npm run lint:djg)
```

### ls-lint
```
$ yarn run lint:ls (or npm run lint:ls)
```

### pylint
```
$ yarn run lint:py (or npm run lint:py)
```

### stylint
```
$ yarn run lint:styl (or npm run lint:styl)
```
