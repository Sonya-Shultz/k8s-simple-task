FROM node:16-alpine
ENV PORT=3000
WORKDIR /myApp
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install --production
COPY . .
EXPOSE 3000
CMD [ "node", "server.js" ]