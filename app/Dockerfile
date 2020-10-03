FROM node:12.18.3-alpine

RUN apk update && \
    apk add git

WORKDIR /usr/src/app

COPY ./app/package*.json ./

RUN npm i

COPY . .

RUN ls -l

EXPOSE 3000
