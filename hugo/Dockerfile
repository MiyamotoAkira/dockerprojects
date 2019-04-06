FROM ubuntu

RUN apt-get update
RUN apt-get install -y curl
RUN apt-get install -y python
RUN apt-get install -y python-pip
RUN pip install --upgrade pip
RUN pip install pygments --upgrade
RUN curl -sLO https://github.com/gohugoio/hugo/releases/download/v0.54.0/hugo_extended_0.54.0_Linux-64bit.deb
RUN dpkg -i hugo_extended_0.54.0_Linux-64bit.deb