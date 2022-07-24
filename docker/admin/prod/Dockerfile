FROM node:lts-alpine

RUN npm install -g http-server

RUN yarn global add @vue/cli

WORKDIR /var/www/admin

CMD [ "http-server", "dist" ]


