FROM python:3.6

ENV PYTHONUNBUFFERED=1
ENV WEBAPP_DIR=/webapp

RUN mkdir $WEBAPP_DIR

WORKDIR $WEBAPP_DIR

ADD requirements.txt $WEBAPP_DIR/

RUN pip install -r requirements.txt

ADD . $WEBAPP_DIR/