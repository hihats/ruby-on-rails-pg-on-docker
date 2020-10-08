FROM node:12.18.4-buster-slim

WORKDIR /var/src/app
COPY package-lock.json .
COPY package.json .
RUN npm install && npm install -g @vue/cli
