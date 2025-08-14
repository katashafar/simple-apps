FROM node:18.17

LABEL email="shafar032@gmail.com"

#Set working directory
WORKDIR /apps

##copy file image
ADD . /apps

#Install dependencies
RUN apt update -y && npm install

#Command to run the app
CMD ["npm", "start"]

#Expose the port the app runs on
EXPOSE 3000
