FROM node:14-alpine AS build

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]
