FROM node:16.13-slim
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 3333
CMD ["node", "server.js"]