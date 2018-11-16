FROM python:2.7-alpine

RUN apk add --no-cache ca-certificates curl

ADD dashboard /

ENTRYPOINT ["/dashboard-installer.sh"]
