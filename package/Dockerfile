FROM registry.suse.com/bci/python:3.12
MAINTAINER support@neuvector.com

RUN pip3 install --upgrade pip setuptools prometheus_client requests
COPY startup.sh /usr/local/bin
COPY nv_exporter.py /usr/local/bin
ENTRYPOINT ["startup.sh"]
