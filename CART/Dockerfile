FROM node:20
WORKDIR /app
COPY package.json .
COPY *.js .
ENV REDIS_HOST="redis"\
    CATALOGUE_HOST="catalogue"\
    CATALOGUE_PORT="8080"
RUN npm install 
CMD ["node","server.js"]