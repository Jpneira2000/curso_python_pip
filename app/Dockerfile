FROM python:latest

RUN mkdir /app

WORKDIR /app

CMD "pip install --upgrade pip"

CMD "pip install -r requirements.txt"

COPY . /app/

CMD "mkdir /app/imgs"

CMD bash -c "while true; do sleep 1; done"