FROM node:24-alpine

WORKDIR /app

COPY . .

RUN npm ci

EXPOSE 4200

ENTRYPOINT ["npx", "ng", "serve", "--host", "0.0.0.0", "--port", "4200"]
