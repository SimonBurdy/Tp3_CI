FROM node:14

COPY package.json yarn.lock ./
RUN yarn install

EXPOSE 3000
CMD yarn start
