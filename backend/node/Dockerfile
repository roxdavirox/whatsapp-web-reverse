FROM node

RUN apt-get update

# Install pip
# RUN apt-get -y install python-pip

# Create app dir
RUN mkdir /www/node
WORKDIR /www/node

# COPY project in app dir
COPY . .

# Install dependencies
### Using NPM
RUN npm install
# RUN npm install -g concurrently

# Pip requirements
# RUN pip install -r requirements.txt

EXPOSE 2018 2019
# Command
## Yarn
#CMD yarn __run_in_docker
CMD npm start
