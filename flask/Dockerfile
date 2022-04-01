FROM python:3.5
WORKDIR /app
ADD . /app
RUN pip install flask
RUN pip install uwsgi
CMD ["uwsgi", "--ini", "uwsgi.ini"]

