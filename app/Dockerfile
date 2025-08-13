FROM node:18.17

# Update package lists and install security updates
RUN apt-get update -y && npm install

#Maintaner Image
LABEL email="shafar032@gmail.com"

# copy file
ADD . /app

#perintah yang dijalan kan ketika container dijalankan
CMD ["npm", "start"]

# Expose the port the app runs on
EXPOSE 3000