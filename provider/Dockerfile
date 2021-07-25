FROM node:14
WORKDIR /usr/src/app
COPY . ./
RUN npm install
RUN npm install express
RUN npm install joi
EXPOSE 3000
CMD ["node", "provider-service.js"]
