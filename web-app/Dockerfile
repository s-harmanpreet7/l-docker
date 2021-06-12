# Specify a base image
FROM node:8-alpine

# Switching working directory inside container
WORKDIR /usr/app

# Install dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default commands
CMD ["npm", "start"]