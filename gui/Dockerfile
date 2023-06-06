FROM node:lts

WORKDIR /app

COPY . .
COPY package.json ./package.json
COPY package-lock.json ./package-lock.json
RUN npm install

CMD ["npm", "run", "dev"]