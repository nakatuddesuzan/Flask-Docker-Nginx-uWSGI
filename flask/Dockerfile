# use Python 3.7.4 container
FROM python:3.7.4-stretch

# set the working directory to app
WORKDIR /app

# copy the current directory components into the container at /app
ADD . /app

#  Install dependancies
RUN pip install -r requirements.txt

#  run a command to start uWSGI
CMD ["uwsgi", "app.ini"]