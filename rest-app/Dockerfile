# Dockerfile
FROM node:16

WORKDIR /my-app

COPY package-lock.json package.json ./

RUN npm install

COPY . .

CMD ["node", "index.js"]