FROM alpine

RUN apk update \
  && apk add python3

WORKDIR /app

COPY ./ /app

RUN pip3 install -r requirements

CMD python3 app.py
