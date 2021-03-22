FROM node:12-alpine

RUN mkdir app
WORKDIR app/

COPY ./package.json package.json 
RUN yarn install

COPY . .
RUN yarn build


ENV HOST 0.0.0.0

CMD yarn start:production
