# Use a Node.js base image
FROM node:16-alpine

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the application code
COPY . .

# Expose port 3009
EXPOSE 3009

# Start the backend server
CMD ["node", "server.js"]

