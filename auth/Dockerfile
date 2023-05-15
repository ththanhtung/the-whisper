from node:alpine

RUN apk add --no-cache npm

workdir ./app

copy ./package.json ./

run npm install

copy ./ ./

cmd ["npm", "run", "start:dev"]