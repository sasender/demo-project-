FROM node:9-slim
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . /app
EXPOSE 51005
CMD ["npm", "start"]