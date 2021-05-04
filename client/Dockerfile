FROM node:16

RUN mkdir -p /app

WORKDIR /app

COPY . .

ADD . /client/

RUN yarn install

RUN yarn global add @quasar/cli

EXPOSE 8080

CMD [ "quasar", "dev" ]