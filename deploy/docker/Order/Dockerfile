FROM openjdk:8-jre

MAINTAINER Sergio.Garcia67@alu.uclm.es

RUN mkdir -p /usr/local/app

#WORKDIR /usr/local/app

COPY drop/*.jar usr/local/app

COPY drop/run.sh /usr/local/app/run.sh

EXPOSE 8080

ENTRYPOINT sh usr/local/app/run.sh
