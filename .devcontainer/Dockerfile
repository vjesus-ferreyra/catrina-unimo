FROM python:3.15.2-trixie

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get -y --no-install-recommends git

RUN pip install --no-cache-dir --upgrade pip \
    && pip install -r --no-cache-dir requirements.txt
