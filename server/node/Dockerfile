FROM node

RUN apt-get update
RUN mkdir /usr/app
WORKDIR /usr/app

COPY package*.json ./
COPY . .
RUN npm install

EXPOSE 2018 2019

CMD npm start
