FROM node:23-alpine

WORKDIR /app

COPY package*.json ./

# Install dependencies
RUN npm install --force

<<<<<<< HEAD
# Copy application source
=======
RUN npm update-browserslist-db@latest

>>>>>>> b1b5e9fbead19ed58473dc103d7e8f08106c5b6b
COPY . .

# Expose frontend port
EXPOSE 3000

# Start the application
CMD ["npm", "run", "start"]
