FROM node:alpine
WORKDIR /user/app

COPY package*.json ./
RUN npm install


EXPOSE 3001
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
