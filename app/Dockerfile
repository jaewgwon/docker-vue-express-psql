# vue-cliを通じてvue create ${APP_NAME}後使用
FROM node:16-slim

RUN mkdir -p /app
WORKDIR /app

RUN npm install -g @vue/cli
COPY /app/package*.json .
RUN npm install --silent

EXPOSE 8080
CMD ["npm", "run", "serve"]