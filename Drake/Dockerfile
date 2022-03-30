FROM node:14.19.1-alpine3.15
WORKDIR /app/drake
EXPOSE 8082
COPY ./.browserslistrc /app/drake
COPY ./*.json /app/drake
COPY ./*.js /app/drake
COPY ./src /app/drake/src
RUN npm install
CMD ["npm","start"]

