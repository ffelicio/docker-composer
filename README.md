# How to use:

1) git clone https://github.com/marcospaegle/docker-composer.git

2) docker up -d

3) To access the containers use(enter in bash): docker exec -it container_name sh

4) To access the NodeJS container use(enter in bash): docker run -v $PWD/:/var/www/html -it marcospaegle/node:6.9.1-v1.0 /bin/bash

# Containers Name

nginx, php, mysql, node

# Contact

Marcos Paegle: <marcos.paegle@gmail.com>
