ARG NODE_VERSION=24.11
FROM node:${NODE_VERSION}-alpine

WORKDIR /app

COPY package.json ./
RUN npm install --omit=dev

COPY server.js ./

EXPOSE 8000

CMD ["node", "server.js"]
