FROM node:14-alpine

WORKDIR /app

COPY package*.json ./

RUN npm ci --production

COPY ./ ./

CMD ["node", "src/server.js"]