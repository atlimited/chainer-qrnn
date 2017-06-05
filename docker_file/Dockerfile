FROM nvidia/cuda:8.0-cudnn5-devel

RUN apt-get update -y && \
    apt-get install -y --no-install-recommends \
    python3-dev \
    python3-pip && \
    rm -rf /var/lib/apt/lists/* /var/cache/apt/archives/*


RUN pip3 install --upgrade pip
RUN pip3 install -U setuptools
RUN pip3 install cupy==1.0.0.1 chainer==2.0.0 h5py

#RUN apt-get -y install build-essential
#RUN apt-get -y install git
#RUN apt-get -y install vim
