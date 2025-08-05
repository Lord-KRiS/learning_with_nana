FROM node:20-alpine

ENV MONGO_DB_USERNAME=root \
    MONGO_DB_USERNAME=password

RUN mkdir -p /home/nodeapp 

COPY ./app /home/nodeapp

WORKDIR /home/nodeapp

RUN npm install

CMD ["node", "server.js"]