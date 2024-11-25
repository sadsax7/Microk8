FROM node:lts-buster
WORKDIR /usr/src/app
COPY package.json package-lock.json ./
RUN npm ci
COPY . .
EXPOSE 5001
CMD ["npm", "start"]
