# Specify a base image
FROM node:14-alpine

# Working Directory in conatiner
WORKDIR /usr/app

# Copy package.json to root of container
COPY ./package.json ./

# Install some dependencies
RUN npm install

# Copy all files to root of container
COPY ./ ./

# Default Commands
CMD [ "npm", "start" ]