# Dockerfile
FROM node:18

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# Expose the port your app runs on
EXPOSE 3000

# Start the app
CMD ["node", "app.js"]
