# Dockerfile for order service
FROM node:22
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3002
CMD [ "node","app.js" ]