FROM node:18-alpine

COPY package*.json /usr/app/

COPY index.js /usr/app/

COPY tracing.js /usr/app/

COPY .env /usr/app/

WORKDIR /usr/app

RUN npm install

EXPOSE 3001

CMD ["node", "index.js"]
