#pull image
FROM node:18.16.0

#directory utama
WORKDIR /Apps

#copy file dari directory apps ke workdir container /apps
ADD /Apps

#build image + module
RUN npm install

#run container + run apps
CMD npm start

#open port
EXPOSE 3000