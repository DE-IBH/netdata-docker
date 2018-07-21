FROM alpine:edge

RUN echo http://dl-cdn.alpinelinux.org/alpine/edge/testing >> /etc/apk/repositories && apk add --no-cache netdata=1.9.0-r0

EXPOSE 19999

ENTRYPOINT ["/usr/sbin/netdata", "-D", "-i 0.0.0.0"]
CMD ["-s", "/host"]
