FROM node:alpine3.19

WORKDIR /app

COPY package-lock.json .
COPY package.json .

RUN npm install

COPY . .