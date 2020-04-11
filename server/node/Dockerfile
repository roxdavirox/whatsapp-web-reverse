FROM node

RUN apt-get update

# Install pip
# RUN apt-get -y install python-pip

# Create app dir
RUN mkdir node
WORKDIR /node

# COPY project in app dir
COPY . .

# Install dependencies
### Using NPM
RUN npm install

EXPOSE 2018 2019
# Command
## Yarn
#CMD yarn __run_in_docker
CMD npm start
