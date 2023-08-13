# nginx_proxy


- Update domains in init-letsencrypt.sh
- Comment out SSL server definitions in data/nginx/app.conf, along with renaming domains.
- Run init-letsencrypt.sh 
- Uncomment and configure SSL definitions
- docker-compose restart
