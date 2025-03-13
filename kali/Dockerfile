# Base image from Kali Linux
FROM kalilinux/kali-rolling

# Set environment variables
ENV DEBIAN_FRONTEND=noninteractive

# Update & install basic tools
RUN apt update && apt upgrade -y && \
    apt install -y \
    kali-linux-headless \
    net-tools \
    curl \
    wget \
    git \
    vim \
    tmux \
    dnsutils \
    nmap \
    iputils-ping \
    socat \
    netcat-traditional \
    python3 \
    python3-pip \
    metasploit-framework \
    john \
    sqlmap \
    wfuzz \
    gobuster \
    hydra \
    aircrack-ng \
    wireshark \
    && apt clean

# Set working directory
WORKDIR /root

# Default shell
CMD ["/bin/bash"]
