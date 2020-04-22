FROM alpine:3.11
RUN apk add --update --no-cache avahi=0.7-r4 augeas=1.11.0-r1

RUN mkdir /opt/avahi
COPY entrypoint.sh /opt/avahi/
RUN chmod +x /opt/avahi/entrypoint.sh

ENTRYPOINT ["/opt/avahi/entrypoint.sh"]

LABEL maintainer="matthew@thompsons.id.au"
