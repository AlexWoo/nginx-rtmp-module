FROM alexwoo/centos-dev
MAINTAINER AlexWoo <wj19840501@gmail.com>
WORKDIR /root

COPY compile /usr/local/bin
COPY valngx  /usr/local/bin
ENV PATH $PATH:/usr/local/nginx/sbin

EXPOSE 8000 80 1935 8080 8081 8082 8083 1936 1937 1938 1939

CMD init
