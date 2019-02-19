
FROM node:latest

MAINTAINER Rémi <remi.sonnier@ecole-isitech.fr>

WORKDIR /opt/app

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]