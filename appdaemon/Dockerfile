FROM python:3.6-stretch

VOLUME /conf 

EXPOSE 5050 
RUN pip3 install --upgrade pip
RUN pip3 install cffi>=1.1
RUN pip3 install appdaemon==3.0.2 

CMD appdaemon -c /conf
