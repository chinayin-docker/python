#
#--------------------------------------------------------------------------
# python 3.12 debian
#--------------------------------------------------------------------------
#

ARG PYTHON_VERSION=3.12.11
FROM python:${PYTHON_VERSION}-slim
LABEL maintainer="chinayin <whereismoney@qq.com>"
ENV DEBIAN_FRONTEND=noninteractive

COPY prebuildfs /

RUN set -eux \
    && install_packages gcc \
    && pip install --no-cache-dir --upgrade pip
