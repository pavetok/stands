FROM nginx

ENV HOME /root

RUN apt-get update && \
    apt-get install -y \
    python-dev \
    python-pip

COPY . /build
WORKDIR /build

RUN pip install -r stand-requirements.txt