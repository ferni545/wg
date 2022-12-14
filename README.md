docker-compose.yml
docker-compose up -d

nano /etc/nginx/sites-available/wg
copy ngi wg to /etc/nginx/sites-available/wg

install ngnix
 apt install nginx
 dnf install ngninx

sudo ln -s /etc/nginx/sites-available/wg /etc/nginx/sites-enabled/wg
sudo systemctl restart nginx

sudo apt install certbot python3-certbot-nginx

sudo certbot --nginx -d your_domain_here