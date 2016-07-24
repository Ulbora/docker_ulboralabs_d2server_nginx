# Usage
docker run --name d2-server-nginx -p 80:80 /
 -v /nginx-conf/nginx.conf:/etc/nginx/nginx.conf:ro /
 -v /nginx-site-conf:/etc/nginx/conf.d:ro -d ulboralabs-nginx