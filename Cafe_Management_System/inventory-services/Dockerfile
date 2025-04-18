FROM node:18

WORKDIR /inventory-services

COPY . .
RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]