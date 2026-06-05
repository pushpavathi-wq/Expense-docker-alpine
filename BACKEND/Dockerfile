FROM node:20.18.3-alpine3.21
# alpine image is nodejs distribution, light weight image
RUN addgroup -S expense && adduser -S expense -G expense
WORKDIR /app/backend
COPY package.json .
COPY *.js .

RUN npm install
ENV DB_HOST="mysql"
CMD ["node" , "index.js"]

