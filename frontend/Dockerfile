FROM node:14-alpine AS builder
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY ./ /app/
CMD ["npm", "start"]
