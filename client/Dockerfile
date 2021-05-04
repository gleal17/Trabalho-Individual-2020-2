FROM node:16

RUN mkdir -p /app

WORKDIR /app

COPY . .

RUN yarn install

RUN yarn global add @quasar/cli

EXPOSE 8080

CMD [ "dev", "quasar" ]