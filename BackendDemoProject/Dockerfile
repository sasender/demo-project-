FROM node
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 51005
CMD ["npm", "start"]