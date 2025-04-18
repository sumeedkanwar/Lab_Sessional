FROM node:18

WORKDIR /customer-service

COPY . .
RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]