FROM node AS app

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g npm@latest
RUN npm install express

COPY . .

EXPOSE 3000

RUN node seeds/seed.js

CMD [ "node", "app.js" ]

# Multi-stage production ready image

FROM node:alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g npm@latest
RUN npm install express

COPY --from=app /usr/src/app/ /usr/src/app/

EXPOSE 3000

RUN node seeds/seed.js

CMD ["node", "app.js"]