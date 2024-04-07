FROM alpine:latest
RUN apk update && apk add --no-cache dnsmasq
ENTRYPOINT ["dnsmasq", "-k"]
