FROM node:alpine

WORKDIR /app

COPY index.js ../package.json ../package-lock.json

RUN npm install

EXPOSE 5050

ENTRYPOINT [ "node", "/app/index.js" ]
