FROM node:12.16-alpine
RUN mkdir node
COPY . ./node
WORKDIR ./node/
RUN npm install
EXPOSE 3004
CMD node index.js
