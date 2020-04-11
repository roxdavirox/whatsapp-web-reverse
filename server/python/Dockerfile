FROM python:2.7

RUN apt-get update

# Install pip
RUN apt-get -y install python-pip

# Create app dir
WORKDIR /usr/app

# COPY project in app dir
COPY . .

# Pip requirements
RUN pip install -r requirements.txt

EXPOSE 2020
# Command
## Yarn
#CMD yarn __run_in_docker
CMD python whatsapp_web_backend.py
