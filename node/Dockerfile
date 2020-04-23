FROM node:12

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /

RUN npm install npm@latest -g
RUN npm install -g pm2

WORKDIR /app
RUN npm install
