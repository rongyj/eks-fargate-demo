FROM node:12

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --production

COPY . /usr/src/app

EXPOSE 3000

CMD ["npm", "start"]