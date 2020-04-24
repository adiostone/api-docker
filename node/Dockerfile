FROM node:12

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /
RUN chmod +x /wait-for-it.sh

RUN npm install -g pm2

WORKDIR /app
