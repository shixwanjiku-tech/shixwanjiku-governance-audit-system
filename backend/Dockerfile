# Backend Dockerfile for Governance Audit System

FROM node:14

# Create and change to the app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy app source code
COPY . .

# Expose the application port
EXPOSE 3000

# Command to start the application
CMD [ "node", "src/app.js" ]