FROM node:alpine3.17

WORKDIR /app

COPY ./package*.json ./

RUN npm i

COPY . .

EXPOSE 8080

ENTRYPOINT node server.js