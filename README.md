docker-compose up

docker-compose exec -u $(id -u $USER) builder bash --rcfile /bashrc
