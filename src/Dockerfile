MAINTAINER ingenieurmt <matthew@thompsons.id.au>

FROM alpine
RUN apk add --update --no-cache avahi augeas

ADD entrypoint.sh /opt/entrypoint.sh

ENTRYPOINT ["/opt/entrypoint.sh"]
