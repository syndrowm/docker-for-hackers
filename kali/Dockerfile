FROM kalilinux/kali-rolling:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get upgrade -y && \
        apt-get install -y netcat-openbsd dnsutils curl nmap ncat \
        iproute2 inetutils-ping ssh 
CMD ["tail", "-f", "/dev/null"]
