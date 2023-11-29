FROM node:14-alpine
WORKDIR /app
COPY ./src/package*.json ./
RUN npm install
EXPOSE 8080
COPY ./src/ .
CMD ["npm", "start"]
