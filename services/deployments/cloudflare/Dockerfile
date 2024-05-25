# Start from the Alpine Linux base image
FROM alpine:latest

# Update APK repositories and install bash, curl, and kubectl
RUN apk update \
    && apk add --no-cache bash curl jq\
    && apk add --no-cache -X http://dl-cdn.alpinelinux.org/alpine/edge/testing kubectl

# Set the default command to bash
CMD ["bash"]
