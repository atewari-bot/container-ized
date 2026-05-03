From node:14-alpine

# RUN apk add --update npm
# RUN apk add --update node.js
WORKDIR /usr/app
#COPY ./ ./
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]