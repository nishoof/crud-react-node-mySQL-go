FROM node:22

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8800
CMD ["node", "index.js"]