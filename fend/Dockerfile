FROM node:14.20.0

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY src/ ./src

copy public/ ./public

CMD ["npm", "start"]
