FROM node:20-alpine

WORKDIR /front/src/app

COPY package*.json .

RUN npm install --omit=dev

COPY . .

EXPOSE 4173

CMD ["npm", "run", "start"]