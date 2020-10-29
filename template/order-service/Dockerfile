FROM node:latest

ENV NODE_ENV production
ENV connectionString order-db
ENV messageBrokerHost message-broker
COPY . /app
WORKDIR /app

RUN npm install

CMD node index.js