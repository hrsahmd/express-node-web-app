# syntax=docker/dockerfile:1
   
FROM node:18-alpine
WORKDIR /myapp
COPY . .
RUN yarn install --production
CMD ["node", "routes/index.js"]
EXPOSE 3000