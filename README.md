# testgt

FROM python:3.6.11-slim-buster

RUN apt-get update \
    &&  apt-get install -y --no-install-recommends \
        wget \
        curl \
        bzip2 \
        apt-transport-https \
        lsb-release \
        gnupg
