FROM mhart/alpine-node:7.10.1

WORKDIR /srv
ADD . .
RUN npm install

EXPOSE 3001
CMD ["node", "server.js"]
