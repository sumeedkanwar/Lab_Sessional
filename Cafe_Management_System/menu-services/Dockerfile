FROM node:18

WORKDIR /menu-services

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD [ "node", "index.js" ]  