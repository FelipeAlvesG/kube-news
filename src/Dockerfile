FROM node:16.15.1
WORKDIR /src
COPY package*.json ./
RUN apt-get install
#RUN apt-get update && apt-get install
#RUN npm clean cache -force
#RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]
