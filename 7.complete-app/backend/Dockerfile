FROM node

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . .

EXPOSE 80

CMD [ "node", "app.js" ]