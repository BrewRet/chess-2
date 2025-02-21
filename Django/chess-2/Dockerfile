FROM python:3.13-alpine

RUN apk update
RUN apk add bash

COPY ./requirements.txt /app/requirements.txt
WORKDIR /app

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
COPY . .


