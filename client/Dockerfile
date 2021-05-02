FROM node:16

RUN mkdir -p /app

WORKDIR /app

COPY . .

RUN yarn global add @quasar/cli

RUN yarn install

EXPOSE $8080

CMD [ "yarn", "dev", "quasar" ]