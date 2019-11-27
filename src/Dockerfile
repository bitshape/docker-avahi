FROM alpine:latest
RUN apk add --update --no-cache avahi augeas

COPY entrypoint.sh /opt/

ENTRYPOINT ["/opt/entrypoint.sh"]

MAINTAINER ingenieurmt <matthew@thompsons.id.au>
