# How to use:

Watch: https://youtu.be/apV2_AwByQU

1) git clone https://github.com/marcospaegle/docker-composer.git

2) cd docker-compose (or your name_folder)

3) docker up -d

OBS: To access the containers use(enter in bash): docker exec -it container_name sh
OBS: To access the NodeJS container use(enter in bash): docker run -v $PWD/:/var/www/html -it marcospaegle/node:6.9.1-v1.0 /bin/bash

# Containers Name

nginx, php, mysql, node

# Contact

Marcos Paegle: <marcos.paegle@gmail.com>
