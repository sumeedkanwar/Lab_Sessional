FROM node:18-alpine

WORKDIR /inventory-services

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3004

CMD [ "node", "index.js" ]  