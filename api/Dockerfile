FROM node:14.17.0-alpine

WORKDIR /usr/src/app
COPY package*.json ./

# install
RUN npm ci

COPY . .

CMD ["npm", "run", "dev"]
