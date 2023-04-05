FROM node:alpine3.10

RUN mkdir /backend

WORKDIR /backend

COPY . .

RUN npm install

EXPOSE 5000

CMD ["npm","start"]