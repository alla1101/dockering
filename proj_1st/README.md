to build docker image with the name : frist_apache

cmd: docker build -t first_apache .

to run it in background

cmd: docker run --name f_apache -d -p 4000:80 first_apache

to stop apache

cmd: docker stop f_apache

to get inside f_apache

cmd: docker exec -it f_apache /bin/bash