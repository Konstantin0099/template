FROM node:16-alpine
WORKDIR /home/ilovedocker/app
RUN pwd && ls -la
COPY package*.json ./packages/
RUN npm i
COPY . ./src
EXPOSE 3032
ENTRYPOINT ["node", "main.js"]