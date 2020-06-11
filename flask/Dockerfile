FROM python:3.7-slim

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

CMD exec gunicorn --bind 0.0.0.0:8000 run:app
