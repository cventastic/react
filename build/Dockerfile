FROM node:18-alpine

RUN mkdir -p /usr/local/app
WORKDIR /usr/local/app
COPY ./app/package.json .
RUN npm install
COPY ./app/ .
 
CMD [ "node", "server.js" ]
