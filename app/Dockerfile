FROM node:18

# Update Alpine packages to fix vulnerabilities
RUN apk update && apk upgrade

LABEL email="shafar032@gmail.com"

# Set working directory
WORKDIR /app

#copy file image
COPY . /app

# Install dependencies
RUN npm install && npm audit fix --force

# Command to run the app
CMD ["npm", "start"]

# Expose the port the app runs on
EXPOSE 3000
