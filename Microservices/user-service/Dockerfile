# Dockerfile for user service
FROM node:22
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3000
CMD [ "node","app.js" ]