FROM ububtu:18.04

MAINTAINER Cyprien Tchatchou

RUN apt-get update -y
RUN apt-get install python3-pip -y

ADD webapi.py /opt/wcfwebapi
ADD requirements.txt /opt/wcfwebapi

Expose 85

CMD [ "/opt/wcfauthapi/webapi.py ]
ENTRYPOINT [ "python 3.8.0" ]

