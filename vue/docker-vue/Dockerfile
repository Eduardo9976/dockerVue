FROM node

RUN mkdir -p /app

WORKDIR /app

RUN npm update -g

RUN npm install -g @vue/cli

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json /app/package.json

RUN npm install --silent

EXPOSE 3000