FROM node:14

WORKDIR /demo-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
