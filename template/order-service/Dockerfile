FROM node:latest

LABEL maintainer="Andri Már Valsson or Ragnar Geir Ragnarsson"

COPY . /app
WORKDIR /app

RUN npm install

ENTRYPOINT [ "npm", "run", "build" ]