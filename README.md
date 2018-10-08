# Python Workshop - DAP-Services

    Ondrej Sika <ondrej@ondrejsika.com>


## Install Python

### Linux (Debian)

```
sudo apt update && sudo apt install -y python3 python3-venv
```

### Docker

```
docker run -ti python:3.6 bash
```

### Download (MacOS, Windows)

<https://www.python.org/downloads/>


## Virtual environment

Create

```
python3 -m venv venv
```

Activate

```
. venv/bin/activate
```

## IPython (better Python shell)

Install

```
pip install ipython
```

Run

```
ipython
```

### Pip

Standart package manager

Install package

```
pip install django
```

## Pipenv

Python Dev Workflow for Humans (<http://pipenv.org>)

Cheatsheet - <https://feici02.github.io/2017/09/24/pipenv-cheatsheet.html>

Install

```
pip install pipenv
```

Install & save package 

```
pipenv install django
```

Install packages from `Pipfile`

```
pipenv install
```


## Django

### Install

Create & activate virtual environment

```
python3 -m venv venv
. venv/bin/activate
```

Install pipenv

```
pip install pipenv
```

Use pipenv to install Django. You can also install ipython for better Django shell.

```
pipenv install django
# or
pipenv install django ipython
```

### Create Django project

```
django-admin startproject example .
``` 
