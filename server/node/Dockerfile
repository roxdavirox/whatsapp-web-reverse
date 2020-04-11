FROM node

RUN apt-get update

WORKDIR /usr/app

COPY package*.json ./
COPY . .
RUN npm install

EXPOSE 2018 2019

CMD npm start
