FROM node:12-alpine

RUN mkdir app
WORKDIR app/
COPY . .
RUN yarn install

RUN yarn build


ENV HOST 0.0.0.0

CMD yarn start:production
