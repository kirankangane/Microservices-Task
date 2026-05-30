# 1. Uses an appropriate Node.js base image (Alpine is lightweight and secure)
FROM node:18-alpine

# 2. Sets a working directory inside the container
WORKDIR /usr/src/app

# 3. Installs dependencies
COPY package*.json ./

# Copy the rest of the application source code
COPY . .

# 4. Exposes the correct port (Change this per service, e.g., 3001, 3002, 3003)
EXPOSE 3000

# 5. Includes a valid CMD instruction to run the application
CMD ["npm", "start"]