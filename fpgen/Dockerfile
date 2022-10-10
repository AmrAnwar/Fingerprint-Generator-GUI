FROM node:16-alpine3.15 as node
WORKDIR /app
COPY . .
RUN npm install
RUN npm run build

FROM nginx:latest
COPY --from=node /app/dist/fpgen /usr/share/nginx/html
EXPOSE 80
