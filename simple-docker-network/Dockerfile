FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && \
    apt install -y --no-install-recommends \
        iproute2 \
        iputils-ping \
        net-tools \
        netcat-openbsd \
        tcpdump \
        tshark \
        python3 \
        python3-pip \
        nano \
        vim \
        ca-certificates \
    && rm -rf /var/lib/apt/lists/*

CMD ["bash"]
