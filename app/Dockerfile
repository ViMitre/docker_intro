FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g npm@latest
RUN npm install express

COPY . .

EXPOSE 3000

RUN node seeds/seed.js

CMD [ "node", "app.js" ]
