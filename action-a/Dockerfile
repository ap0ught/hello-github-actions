FROM docker/whalesay:latest
MAINTAINER Misa Ogura misa.ogura01@gmail.com

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
