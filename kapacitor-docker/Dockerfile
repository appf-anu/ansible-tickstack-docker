FROM kapacitor:alpine

RUN apk add --no-cache \
    tzdata \
    python3 \
    py3-pip \
    py3-yaml \
 && pip3 install requests PyGithub \
 && rm -rf /var/cache/apk/*

