# Base Image
FROM node:alpine

# Working directory
WORKDIR '/app'

COPY ./package.json ./

RUN npm install

COPY . .

CMD [ "npm", "start" ]