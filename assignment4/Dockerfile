FROM ubuntu
RUN apt-get update -y
RUN DEBIAN_FRONTEND="noninteractive" apt-get install tzdata -y
RUN apt-get install apache2 -y
ENTRYPOINT apachectl -D FOREGROUND
