FROM node:4.2.2
MAINTAINER fj.lopez@ugto.mx

WORKDIR /build/app/

COPY package.json /tmp/package.json
RUN cd /tmp && npm install && cp -a /tmp/node_modules .

COPY . .