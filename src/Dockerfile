FROM node:16.13.2
WORKDIR /myapp
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]