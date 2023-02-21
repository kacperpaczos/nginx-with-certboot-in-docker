# nginx-with-certbot-in-docker

## Create SSL
sudo docker compose up
sudo docker compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d dysk.paczos.org

Remember:
1 Off SSL
2 Off redirect from http to https
