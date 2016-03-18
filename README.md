# docker-mm-nginx-logstash
Nginx server for the mm project to proxy to logstash

Run with:
docker run -p 443:443 -e ETCD_HOST=localhost -e ETCD_PORT=4001 rsmith/docker-mm-nginx