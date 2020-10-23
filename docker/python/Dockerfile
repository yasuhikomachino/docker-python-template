FROM python:3.9.0
SHELL ["/bin/bash", "-oeux", "pipefail", "-c"]

WORKDIR /workspace

COPY src/requirements.txt .
RUN pip install -r requirements.txt 
