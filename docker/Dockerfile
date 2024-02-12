# Use the official Node.js image with Alpine as the base image
FROM node:alpine

# Set the working directory to /app
WORKDIR /app

# Add line to Dockerfile
RUN apk --no-cache add docker-compose

# Copy the current directory contents to the container at /app
COPY . .

# Make port 3000 available to the world outside this container
EXPOSE 3000
EXPOSE 80

# Command to run the application
CMD [ "npm", "run", "start" ]
