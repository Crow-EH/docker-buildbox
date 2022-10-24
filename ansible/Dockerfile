FROM python:3.11.0rc2-slim-buster

ADD requirements.txt .

RUN pip install -U pip pipenv boto3 awscli && \
    pip install -r requirements.txt &&  \
    rm -rf /var/cache/apk/*
