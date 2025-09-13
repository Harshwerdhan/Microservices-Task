# Docker file for gateway service
FROM node:22
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3003
CMD [ "node","app.js" ]