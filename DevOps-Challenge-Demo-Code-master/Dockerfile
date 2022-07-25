FROM python:3.7
COPY . /DevOps-Challenge-Demo-Code-master
WORKDIR /DevOps-Challenge-Demo-Code-master
RUN pip install -r requirements.txt
EXPOSE 8000
#RUN apt-get update && apt-get install -y redis-server  && /usr/bin/redis-server
CMD export $(cat .env | xargs) && python hello.py
