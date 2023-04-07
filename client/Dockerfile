FROM node:16.20.0-alpine3.16

RUN mkdir /client

WORKDIR /client

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","start"]