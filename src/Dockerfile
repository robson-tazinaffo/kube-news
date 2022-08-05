FROM node:16.13.2
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8085
CMD ["node", "server.js"]