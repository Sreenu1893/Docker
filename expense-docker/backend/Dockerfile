FROM node:20
WORKDIR /opt/backend
COPY package.json .
EXPOSE 8080
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]
