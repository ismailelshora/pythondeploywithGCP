FROM python:3.9-alpine
COPY . /DevOps-Challenge-Demo-Code-master
WORKDIR /DevOps-Challenge-Demo-Code-master
RUN pip install -r requirements.txt
RUN apk --update add redis
EXPOSE 8000
CMD export $(cat .env | xargs) && redis-server --daemonize yes && python hello.py
