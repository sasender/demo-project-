FROM node:alpine
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
RUN npm start
COPY . .
EXPOSE 51005
CMD ["npm", "start"]