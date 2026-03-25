FROM node:18

# Container me working directory
WORKDIR /app

# Root ke package.json copy karo
COPY package*.json ./    

# Dependencies install karo
RUN npm install

# Frontend folder ka code copy karo /app/frontend me
COPY frontend ./frontend   

# Frontend folder me work directory set karo
WORKDIR /app/frontend

EXPOSE 3000

# Frontend start command
CMD ["npm", "start"]