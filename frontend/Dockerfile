# Use an official Node.js runtime as a parent image
FROM node:18

# Set the working directory in the container
WORKDIR /app

# Copy the package.json and package-lock.json files
COPY package.json .

# Install dependencies
RUN npm install

# Copy the application code
COPY . .

# Expose the port React is running on
EXPOSE 3000

# Command to start the React app
CMD ["npm", "start"]
