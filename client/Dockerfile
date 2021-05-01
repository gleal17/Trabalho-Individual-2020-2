FROM node:16

RUN mkdir -p /app/client
WORKDIR /app/client

COPY ./client/package.json .
COPY ./client/yarn.lock .

RUN yarn
RUN yanr install

COPY ./client .

EXPOSE 8080

CMD [ "yarn", "run", "dev" ]