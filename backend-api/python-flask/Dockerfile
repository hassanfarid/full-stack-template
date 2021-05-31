FROM python:3.9-slim-buster

ENV APPPATH /opt/flaskapp
COPY . $APPPATH
WORKDIR $APPPATH/app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]