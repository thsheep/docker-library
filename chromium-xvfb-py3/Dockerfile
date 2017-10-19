FROM markadams/chromium-xvfb:latest
MAINTAINER Gtao@you_tell.me
RUN apt-get install -y gcc make zlib1g-dev wget && \
    wget -O /tmp/Python-3.6.0.tar.xz https://www.python.org/ftp/python/3.6.0/Python-3.6.0.tar.xz && \
    cd /tmp/ && \
    tar xJf Python-3.6.0.tar.xz && \
    cd Python-3.6.0 && \
    ./configure &&  make && make install && \
    ln -s /usr/local/bin/python3 /usr/bin/python && \
    ln -s /usr/local/bin/pip3 /usr/bin/pip
CMD ["python", "-V"]