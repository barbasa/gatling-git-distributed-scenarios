FROM barbasa/gatling-base:latest

USER root
ADD build.sbt /home/gatling/gatling-git
ADD project /home/gatling/gatling-git/project
ADD src /home/gatling/gatling-git/src

RUN chown -R gatling:gatling .
