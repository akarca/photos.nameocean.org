# Docker Compose
```bash
# start
docker compose up -d

# update
docker compose down
docker compose pull
docker compose up -d
```

# Nginx
```bash
# setup
cd /usr/local/etc/nginx/servers
ln -s /Users/serdar/workspace/reverseproxy.io/__conf/nginx.conf /usr/local/etc/nginx/servers/n3backup.nameocean.org.conf

# restart nginx
brew services restart nginx
```
