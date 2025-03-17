FROM node:20.18.3-alpine3.21 AS builder
WORKDIR /opt/backend
COPY package.json .
RUN addgroup -S expense
RUN adduser -S expese -G expense
RUN mkdir /opt/backend
RUN chown -R expense:expense /opt/backend
EXPOSE 8080
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
USER expense
CMD ["node", "index.js"]
