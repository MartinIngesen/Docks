Docker containers

Build by running:
run make.sh to build the container.

Run the container using:

sudo docker run -v ~/pwn:/pwn -dit pwn:pwn

Now access the container using:

sudo docker exec -it CONTAINER_ID /bin/bash
