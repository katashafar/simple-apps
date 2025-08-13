FROM node:18.16-slim

# Update package lists and install security updates
RUN apt-get updatec -y && npm install


# copy file
ADD . /app

#perintah yang dijalan kan ketika container dijalankan
CMD ["npm", "start"]

# Expose the port the app runs on
EXPOSE 3000