FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
CMD echo "Hello from Develop branch!!!"
CMD echo "Hello from Develop branch!!!!!!!!!!!!!!!"
