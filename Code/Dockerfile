FROM node:current-slim

WORKDIR /usr/src/app

RUN npm install -g http-server

EXPOSE 8080
COPY . .

CMD [ "http-server"]

