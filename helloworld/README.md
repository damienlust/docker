simple Dockerfile to display Helloword in a nginx server

docker build -t damienlust/hello-world-nginx .
docker run -p 8090:80 damienlust/hello-world-nginx

Accessible on http://localhost:8090
