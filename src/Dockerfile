FROM node

WORKDIR /conv

COPY ["package.json", "package-lock.json*", "./"]
RUN npm install --production
COPY . .

EXPOSE 8080

CMD ["node", "server.js"]