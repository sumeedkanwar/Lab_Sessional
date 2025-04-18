FROM node:18-alpine

WORKDIR /api-gateway

COPY . .
RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]