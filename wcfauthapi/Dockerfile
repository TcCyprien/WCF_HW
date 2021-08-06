From ubuntu:18.04

MAINTAINER Cyprien Tchatchou

RUN apt-get update -y
RUN apt-get install python3-pip -y

ADD authapi.py /opt/wcfauthapi
ADD requirements.txt /opt/wcfauthapi

Expose 80

CMD [ "/opt/wcfauthopi/autoapi.py ]
ENTRYPOINT [ python 3.8.0 ]  

