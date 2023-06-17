FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./
COPY . /usr/src/app

RUN npm install


CMD [ "npm", "run", "dev" ]