FROM node:12-alpine

WORKDIR /usr/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 51005
CMD ["npm", "start"," "--keep-alive",]