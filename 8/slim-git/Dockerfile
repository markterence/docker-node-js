FROM node:8.11.2-slim
LABEL maintainer="https://keybase.io/coffeekitkat"
RUN apt-get update && apt-get install \ 
	git \
	-yq --no-install-suggests --no-install-recommends \
	&& apt-get clean && rm -rf /var/lib/apt/lists/*
CMD [ "node" ]