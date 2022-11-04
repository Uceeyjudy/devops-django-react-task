FROM node:alpine
WORKDIR /frontend
COPY package*.json ./
RUN npm install
COPY . .
RUN npm start
EXPOSE 3000
CMD ["npm", "run", "build"]
