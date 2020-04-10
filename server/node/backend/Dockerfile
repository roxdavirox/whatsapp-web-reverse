FROM node

RUN apt-get update

# Install pip
# RUN apt-get -y install python-pip

# Create app dir
RUN mkdir node
WORKDIR /node
RUN mkdir backend
WORKDIR /node/backend

# COPY project in app dir
COPY . .

WORKDIR /node
RUN mkdir client
WORKDIR /node/client
COPY ../client/ .

WORKDIR /node/backend
# Install dependencies
### Using NPM
RUN npm install

EXPOSE 2018 2019
# Command
## Yarn
#CMD yarn __run_in_docker
CMD npm start
