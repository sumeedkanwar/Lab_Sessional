FROM node:18-alpine

WORKDIR /customer-services


COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3005

CMD [ "node", "index.js" ]