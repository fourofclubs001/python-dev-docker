# Base container for python development

Steps:

- docker-compose up --build -d
- open container with VSCode extension Dev Containers
- open a terminal on the container and execute cat ~/.ssh/id_rsa.pub
- copy the generated key on your git account
- enjoy