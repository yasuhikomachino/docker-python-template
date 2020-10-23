# docker-python-template

A template to quickly build a python development environment.

## Environment

- Docker 19.03.12
- docker-compose 1.26.2

## Stack

- Python 3.9.0
- mypy 0.79
- flake8 3.8.4
- black 20.8b1

## Setup

```
$ docker-compose build
```

## Run python container 

```
$ docker-compose run --rm python bash
```

```
# python --version
Python 3.9.0

# python sample.py
Hello, world!
```
