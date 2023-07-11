# flask_microservice

Flask API connected with Django 'microservice_python'

# flask_installation

sudo apt install python3-flask

# Docker compose commands

docker-compose up --build (permission issue use 'sudo')

docker image prune -a (Removing all unused images)

# Bug Fixes

## db container not stop or down

sudo aa-remove-unknown ( not nessasary to remove all unknown author files and programs)

docker container kill $(docker ps -q)
docker-compose down

# Install Postman to check API (not needed in production server)

sudo snap install postman
