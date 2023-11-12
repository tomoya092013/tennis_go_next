FROM node:18.17.1

WORKDIR /app

COPY package.json package-lock.json ./

COPY . .

RUN npm install

RUN npm run build

EXPOSE 3000

CMD ["npm","run","dev"]
