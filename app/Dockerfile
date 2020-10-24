FROM python:2.7-onbuild
EXPOSE 8000

WORKDIR /app

ADD requirements.txt /app/requirements.txt
ADD app.py /app
RUN pip install -r /app/requirements.txt

CMD [ "python", "app.py" ]