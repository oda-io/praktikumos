FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    build-essential \
    gcc \
    make \
    qemu \
    git \
    curl \
    wget \
    nano \
    iputils-ping \
    procps \
    net-tools \
    python3 \
    && apt-get clean

WORKDIR /xv6

# Clone repo xv6
RUN git clone https://github.com/mit-pdos/xv6-public.git .

CMD ["/bin/bash"]

