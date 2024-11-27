FROM node:lts-alpine
WORKDIR /server
COPY ./package*.json ./
RUN npm install 
COPY . .
EXPOSE 9000
CMD ["npm", "start"]