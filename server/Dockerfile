FROM node:16

WORKDIR /app

# Copy package.json and package-lock.json from the server directory
COPY package.json package-lock.json ./

RUN npm install

COPY server/ .

EXPOSE 5000

CMD ["node", "src/index.js"]

