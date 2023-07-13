FROM node:16.16

RUN apt-get update -qq && yarn global add @vue/cli

WORKDIR /app

CMD ["yarn", "serve-dev"]