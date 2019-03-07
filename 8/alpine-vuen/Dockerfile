FROM node:8.14-alpine
LABEL maintainer="https://keybase.io/coffeekitkat"
RUN apk add --no-cache\
    libpng-dev \
    autoconf \
    automake \
    make \
    g++ \
    libtool \
    nasm
RUN rm -rf /tmp/*
CMD [ "node" ]