FROM node

RUN mkdir -p /app

WORKDIR /app

RUN apk update && apk upgrade

RUN apk add git

COPY package.json .

RUN npm install

EXPOSE 3000