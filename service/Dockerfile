# Use Node.js 20 Alpine as the base image
FROM node:20-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the built app from the dist folder
COPY dist/ ./dist/

# Expose the port your app runs on
EXPOSE 3000

# Command to run your app
CMD ["node", "dist/app/index.js"]