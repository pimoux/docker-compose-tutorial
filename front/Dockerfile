FROM node
WORKDIR /var/www/front
COPY package.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]