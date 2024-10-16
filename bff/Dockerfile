FROM node:latest

WORKDIR /app

COPY package*.json ./

COPY elm-tooling.json ./

RUN npm install

COPY . .

EXPOSE 1234

CMD ["npm", "run", "start"]
