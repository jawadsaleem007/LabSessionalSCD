FROM node:12.16-alpine
RUN mkdir node
COPY . ./node
WORKDIR ./node/
RUN npm install
EXPOSE 3003
CMD node index.js
