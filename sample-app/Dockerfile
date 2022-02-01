FROM node:16-slim

WORKDIR /app

COPY . /app/sample-app

WORKDIR /app/sample-app

RUN yarn install

RUN yarn build
