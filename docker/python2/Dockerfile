FROM nvidia/cuda:7.5-cudnn5-devel

RUN apt-get update -y && \
    apt-get install -y --no-install-recommends \
    python-dev \
    python-pip && \
    rm -rf /var/lib/apt/lists/* /var/cache/apt/archives/*

RUN pip install cupy==4.0.0b1 chainer==4.0.0b1
