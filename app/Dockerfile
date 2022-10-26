FROM node:latest

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package.json package-lock.json ./
RUN npm install

# Copy app source
COPY . ./

# Expose port
EXPOSE 8080

# Set command for startup
CMD [ "node", "index.js" ]