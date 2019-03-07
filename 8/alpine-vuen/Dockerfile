FROM node:8.14-alpine
LABEL maintainer="https://keybase.io/coffeekitkat"

RUN apk add --no-cache --virtual build-dependencies \
		autoconf \
    automake \
    bash \
    g++ \
    libc6-compat \
    libjpeg-turbo-dev \
    libpng-dev \
    make \
    nasm

RUN rm -rf /tmp/* && apk del build-dependencies
CMD [ "node" ]