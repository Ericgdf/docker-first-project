# Dockerfile
FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
COPY public public
COPY src src
RUN npm i

CMD npm start