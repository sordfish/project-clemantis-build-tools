FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \ 
    build-essential \
    cmake \ 
    clang \
    bison \
    flex \
    libreadline-dev \ 
    gawk \
    tcl-dev \
    libffi-dev \ 
    git \
    graphviz \ 
    xdot \
    pkg-config \ 
    python3 \
    libboost-system-dev \
    libboost-python-dev \
    libboost-filesystem-dev \
    zlib1g-dev

RUN git clone https://github.com/YosysHQ/yosys.git && \
    cd yosys && \
    make && \
    make install

 
