FROM node:18-alpine

RUN mkdir -p /usr/local/app
WORKDIR /usr/local/app
RUN npx create-react-app tictactoe
WORKDIR /usr/local/app/tictactoe
 
CMD [ "npm", "start" ]
