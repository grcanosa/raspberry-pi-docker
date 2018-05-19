FROM arm32v7/python:3.6

EXPOSE 5050

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY appdaemon_git/ .
RUN ls -la
# Install
RUN pip3 install .

# Start script
RUN chmod +x /usr/src/app/dockerStart.sh
CMD [ "./dockerStart.sh" ]