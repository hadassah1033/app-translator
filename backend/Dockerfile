FROM node:18-alpin
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 
CMD ["npm", "start"]