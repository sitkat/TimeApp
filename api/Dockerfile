FROM node:alpine

WORKDIR /application
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm", "rum", "dev"]
