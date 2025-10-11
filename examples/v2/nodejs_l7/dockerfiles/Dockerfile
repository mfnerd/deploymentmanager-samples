FROM node:24.10.0-alpine3.22

RUN mkdir /var/www/
ADD service.js /var/www/service.js
WORKDIR /var/www/
RUN npm install mysql

CMD ["node", "service.js"]
