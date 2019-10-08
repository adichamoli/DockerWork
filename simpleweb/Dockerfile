#Specify Vase Image
FROM node:alpine

#Specifying Working Dir
WORKDIR /usr/app

#Copy Required Application files
COPY ./ ./

#Install Dependencies
RUN npm install

#Run Default Command
CMD ["npm","start"]