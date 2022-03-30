FROM node:14.19.1-alpine3.15
WORKDIR /app/node
EXPOSE 8081
COPY ./*.json /app/node
COPY ./*.js /app/node
RUN npm install
CMD ["npm","start"]

