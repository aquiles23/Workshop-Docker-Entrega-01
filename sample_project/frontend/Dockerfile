FROM node:14

WORKDIR /frontend

COPY ["package*.json", "yarn.lock", "./"]

RUN yarn install

CMD ["yarn", "dev"]
