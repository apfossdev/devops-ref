FROM node:22-alpine

WORKDIR /app

COPY ./package.json ./package.json
COPY ./package-lock.json ./package-lock.json
RUN npm install

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]
