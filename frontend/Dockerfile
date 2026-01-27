FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
# Spelling fix: axios (double 's' nahi)
RUN npm install axios 
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]