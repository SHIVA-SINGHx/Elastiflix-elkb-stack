FROM node:23-alpine

WORKDIR /app

COPY package*.json ./

# Install dependencies
RUN npm install --force

# Copy application source
COPY . .

# Expose frontend port
EXPOSE 3000

# Start the application
CMD ["npm", "run", "start"]
