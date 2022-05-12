FROM node:16.14.2
RUN mkdir /app && apt-get update && apt-get install -y default-mysql-client
WORKDIR /app
COPY ./package.json /app
COPY ./package-lock.json /app
RUN npm install
