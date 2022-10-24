FROM node:16.3.0-alpine

WORKDIR /cloudl-server

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]