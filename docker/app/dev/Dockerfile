FROM node:lts-alpine

RUN npm install -g http-server

RUN yarn global add @vue/cli

WORKDIR /var/www/app

CMD [ "yarn", "serve" ]


