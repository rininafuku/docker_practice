FROM ubuntu:23.04

RUN apt update \
  && apt install -y apache2

CMD [ "apachectl","-D","FOREGROUND" ]
