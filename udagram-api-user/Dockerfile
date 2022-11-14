FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm --version
RUN npm i
COPY . .
EXPOSE 9090
CMD ["npm", "run", "prod"]