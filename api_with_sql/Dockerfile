FROM node:hydrogen-slim

WORKDIR /app

COPY package.json ./

COPY package-lock.json ./
#COPY package*.json ./

RUN npm install

COPY index.js ./

CMD ["npm", "start"]