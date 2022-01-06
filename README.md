# docker-compose-experiments
experimenting with docker compose

docker build -t my-apache2 .
docker run -d --name my-apache-container -v "$PWD/app/":/usr/local/apache2/htdocs/ -p 8080:80 my-apache2