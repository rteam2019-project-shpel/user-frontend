FROM node:10
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm ci --only=master
COPY . .
EXPOSE 2000
CMD ["npm", "start"]
