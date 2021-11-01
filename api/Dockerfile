# src/app.jsがNodeアプリのEntry Pointになるように想定
FROM node:16-slim

RUN mkdir -p /server

WORKDIR /server

COPY /api/package*.json .
RUN npm install -g nodemon && npm install --silent
COPY . .
CMD ["npm", "run", "start"]

EXPOSE 3000