FROM node:16

# Create app directory
WORKDIR /home/roberto/NUS/SEPP/OTOT/A1/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

# Expose port
EXPOSE 8080

# Set command for startup
CMD [ "node", "index.js" ]