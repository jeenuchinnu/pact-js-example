FROM node:14
WORKDIR /usr/src/app
COPY ../package*.json ./
COPY . ./
RUN npm install
RUN npm install express
RUN npm install joi
EXPOSE 3000
CMD ["node", "provider-service.js"]
