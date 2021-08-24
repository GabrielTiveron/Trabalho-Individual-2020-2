FROM node:13.14-alpine

WORKDIR /src
COPY package*.json ./
RUN yarn global add @quasar/cli
COPY . .

RUN yarn install

EXPOSE 3000

CMD ["quasar", "dev"]
