FROM node:16.14.2
RUN mkdir /app && apt-get update
WORKDIR /app
COPY ./package.json /app
COPY ./package-lock.json /app
RUN npm install
