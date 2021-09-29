FROM node:14.17.5
WORKDIR /app
COPY package*.jason ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]