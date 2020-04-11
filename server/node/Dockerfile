FROM node

RUN apt-get update

# Create app dir
# RUN mkdir code
WORKDIR /usr/app

# COPY package*.json ./
COPY . .
RUN npm install

EXPOSE 2018 2019

CMD npm start
