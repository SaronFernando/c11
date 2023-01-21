FROM python:3-slim-buster
COPY . /python-flask
WORKDIR /python-flask/c11
RUN pip install flask
ENTRYPOINT ['python','snows insurance/main.py']
