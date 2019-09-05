# Specify a base image
FROM node:alpine 

#install some dependencies
#./ is used to indicate the current directory
#workdir <dir-name>-- sets the default working directory
workdir /usr/app
copy ./package.json ./
run npm install

copy ./ ./

#default command
CMD ["npm","start"]