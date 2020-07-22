# Base image
FROM node:alpine

# Folder
WORKDIR /usr/app

# Dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]