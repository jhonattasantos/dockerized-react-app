# build environment
FROM node:14-alpine

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package*.json /app/

RUN yarn install --silent

EXPOSE 3000

CMD ["yarn", "start"]