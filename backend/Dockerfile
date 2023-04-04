FROM node:alpine3.10

RUN mkdir /client

WORKDIR /client

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","start"]