FROM mcr.microsoft.com/devcontainers/python:3.12

RUN pwd && ls -a

COPY requirements.txt /tmp/requirements.txt

RUN pip install jupyterlab jupyterlab-deck \
    && pip install -r /tmp/requirements.txt
