FROM alexwoo/centos-dev
MAINTAINER AlexWoo <wj19840501@gmail.com>
WORKDIR /root

COPY compile /usr/local/bin
COPY valngx  /usr/local/bin
ENV PATH $PATH:/usr/local/nginx/sbin

CMD init
