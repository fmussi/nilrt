Run the following command to build the container:
cd to the current folder

export UID=$UID
UID=${UID} GID=${GID} docker-compose -f docker-compose.yml up <container name, e.g. oebuild>

to run the container:

docker start <name of the container>

to connect with a shell:

docker exec -it <name of the container> /bin/bash


