FROM alpine:latest
RUN apk add --no-cache hostapd
COPY hostapd.conf /etc/hostapd/hostapd.conf
ENTRYPOINT ["hostapd", "/etc/hostapd/hostapd.conf"]
