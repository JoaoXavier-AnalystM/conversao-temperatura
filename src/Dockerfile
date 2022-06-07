FROM node:16.15.0

WORKDIR /app

COPY ./package*.json /app/
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
