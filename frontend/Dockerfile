FROM node:alpine

WORKDIR /application
COPY . .
RUN npm install
EXPOSE 3000
CMD ["npm", "run", "dev"]