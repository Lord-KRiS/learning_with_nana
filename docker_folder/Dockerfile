FROM node:20-alpine

ENV MONGO_DB_USERNAME=root \
    MONGO_DB_USERNAME=password

RUN mkdir -p /home/app 

COPY . /home/app

WORKDIR /home/app

RUN npm install

CMD ["node", "server.js"]