FROM alpine:3.15

RUN apk add --update --no-cache \
    strongswan \
    vim \
    iproute2 \
    curl

ENTRYPOINT ["/usr/sbin/ipsec"]

CMD ["start", "--nofork"]