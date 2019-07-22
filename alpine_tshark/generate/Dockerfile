FROM alpine:latest
RUN apk update && apk add bash
ADD scripts/ /root/
ENTRYPOINT ls /root/
