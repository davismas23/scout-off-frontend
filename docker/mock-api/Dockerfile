ARG NODE_VERSION=24.11
FROM node:${NODE_VERSION}-alpine

WORKDIR /app

COPY package.json ./
COPY server.js ./

EXPOSE 4000

CMD ["node", "server.js"]
