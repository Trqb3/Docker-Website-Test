docker build -t docker-website-test:v1 .
docker images
docker run -d -p 80:80 --name docker-website-test docker-website-test:v1
docker ps
