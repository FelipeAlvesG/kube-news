FROM node:16.15.1
WORKDIR /usr/app
COPY package*.json ./
RUN npm clean cache -force
RUN npm install
COPY ./ ./
EXPOSE 8080
CMD ["node","server.js"]
