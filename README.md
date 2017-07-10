# tiles-proxy
proxy for mbtiles server

docker run --restart unless-stopped  --name tilesproxy -v /etc/letsencrypt/archive/tiles.red-meteor.com:/ssl/docker -p 443:443 -p 80:80 -d royhobbstn/tiles-proxy
