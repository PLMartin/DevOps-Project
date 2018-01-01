FROM node:8

WORKDIR /usr/src/app

COPY wik-devops-3tp/package*.json ./

COPY wik-devops-3tp/app.js ./

RUN npm install

EXPOSE 8080

CMD ["npm", "start"]
