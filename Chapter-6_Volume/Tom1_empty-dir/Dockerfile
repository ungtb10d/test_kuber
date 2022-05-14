FROM ubuntu:latest 

ADD fortuneloop.sh /bin/fortuneloop.sh
RUN apt-get update && apt-get -y install fortune && chmod +x /bin/fortuneloop.sh

ENTRYPOINT [ "bash", "-c", "/bin/fortuneloop.sh" ]
