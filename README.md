# project-setup

Simple Rails Setup with Docker and Docker Compoese. 

1) To create new app, executes this command. 

docker run -it --rm --user "$(id -u):$(id -g)" -v "$PWD":/usr/src/app -w /usr/src/app rails rails new --skip-bundle *[NAME_OF_APP]* --database=postgresql

