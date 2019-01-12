FROM node:10.1-alpine

WORKDIR /src/app

COPY ./package.json .

RUN ["npm", "install"]

COPY . .
