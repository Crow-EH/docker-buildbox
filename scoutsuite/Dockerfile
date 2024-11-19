FROM python:3.12.0b2-slim-buster

ADD requirements.txt .

RUN pip install -U pip && \
    pip install pipenv awscli boto3 && \
    pip install -r requirements.txt
