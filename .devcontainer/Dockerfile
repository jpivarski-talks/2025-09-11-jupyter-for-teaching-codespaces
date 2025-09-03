FROM mcr.microsoft.com/devcontainers/python:3.12

RUN pip install jupyterlab && pip install -r requirements.txt

COPY requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt
