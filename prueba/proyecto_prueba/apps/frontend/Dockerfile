# FROM node:lts-alpine
FROM node:10

# RUN mkdir /data

RUN mkdir /app

COPY app/package*.json /app/

# make the 'app' folder the current working directory
WORKDIR /app/

RUN npm installs












# # FROM node:10.9-slim
# LABEL "MAINTAINER"="GeraldineEchavarria"

# RUN mkdir /app
# COPY app/package.json /app/

# # # WORKDIR /app/
# # RUN npm install
# # RUN apt-get update
# # RUN apt-get install curl -f
# # RUN curl -sL https://deb.nodesource.com/setup_10.x | bash 
# # RUN apt-get install -y nodejs
# # # RUN apt-get install npm

# # RUN npm upgrade