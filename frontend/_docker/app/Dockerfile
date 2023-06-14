FROM node:20-alpine3.17 AS build
WORKDIR /var/www/frontend
COPY ./package.json ./
RUN npm install
COPY . .
