# nginx-with-certbot-in-docker

## Create SSL
sudo docker compose up
sudo docker compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d dysk.paczos.org
