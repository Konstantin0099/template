FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY ./packages/package*.json ./
RUN pwd && ls -la && npm i
COPY . ./src
RUN pwd && ls -la
EXPOSE 3032
ENTRYPOINT ["node", "main.js"]