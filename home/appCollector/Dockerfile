FROM python:3.8

WORKDIR /app

COPY requirements.txt /tmp/

RUN apt-get update && \
    apt-get install -y libglib2.0-dev bluetooth bluez && \
    apt-get clean && \
    pip3 install --requirement /tmp/requirements.txt

COPY ./src .
COPY docker-entrypoint.sh . 

ENTRYPOINT ["./docker-entrypoint.sh"]
CMD ["python3"]
