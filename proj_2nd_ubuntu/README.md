to build docker image with the name : first_ubuntu

cmd: docker build -t ubuntu_server .

TODO: didn't build it yet,waiting to learn volumes first

docker run --name ubnutu_s -d -p 4000:80 ubuntu_server

to get inside ubuntu_s

cmd: docker exec -it ubuntu_s /bin/bash