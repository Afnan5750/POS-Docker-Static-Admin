# backend/Dockerfile

FROM node:20

WORKDIR /app

COPY package*.json ./
RUN npm install

# Copy code + env
COPY . .

# Expose port
EXPOSE 5000

CMD ["npm", "start"]
