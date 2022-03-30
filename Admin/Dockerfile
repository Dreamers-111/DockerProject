FROM node:14.19.1-alpine3.15
WORKDIR /app/admin
EXPOSE 8083
COPY ./.browserslistrc /app/admin
COPY ./*.json /app/admin
COPY ./*.js /app/admin
COPY ./src /app/admin/src
RUN npm install
CMD ["npm","start"]

