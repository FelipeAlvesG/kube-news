FROM node:16.15.1
WORKDIR /app
COPY package*.json ./
RUN apt-get install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]
