FROM node:9-slim
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . /app
EXPOSE 51005
#NODE_ENV=production node app.js

CMD ["node", "index.js"]