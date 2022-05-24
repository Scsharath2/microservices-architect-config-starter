#baseiamge
FROM node:8 
MAINTAINER scsharath2@gmail.com Sarat Chandra G

# Where the app should be deployed
WORKDIR /app 
#copy the all the code from local to docker image
COPY . . 

RUN npm install express #build the node code
RUN npm install 

EXPOSE 8080 # exposing the application

#Runs in development Mode 
#Once the image is build, start  the application
CMD ["npm", "start"] 