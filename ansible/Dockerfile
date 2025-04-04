FROM python:3.12.0b2-slim-buster

ADD requirements.txt .

RUN pip install -U pip pipenv boto3 awscli && \
    pip install -r requirements.txt &&  \
    rm -rf /var/cache/apk/*
