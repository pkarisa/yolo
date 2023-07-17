FROM node:19.0.1.alpine

WORKDIR /app

COPY package*json /app/

RUN npmi

COPY . /app/

CMD ['npm',"start"]