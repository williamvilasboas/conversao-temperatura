FROM node:16-alpine
WORKDIR /srv/app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
