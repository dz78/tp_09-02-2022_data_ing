FROM node:14

WORKDIR /frontdends
COPY package.json .
RUN npm install
COPY . .
CMD npm start
