FROM python:3.9-slim-buster

WORKDIR /app

ADD . /app

RUN pip install pipenv

RUN pipenv install --system

WORKDIR /app/djangoapp

CMD ["python", "manage.py", "runserver"]