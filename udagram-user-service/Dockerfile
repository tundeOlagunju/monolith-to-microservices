FROM node:13

WORKDIR usr/src/app

# package.json and package-lock.json
COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 8080

CMD ["npm","run","prod"]