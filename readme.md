## Config NGINX redirection vers nodeJs

```cmd
sudo apt install nginx
sudo nano /etc/nginx/sites-available/domain.extension
sudo ln -s /etc/nginx/sites-available/domain.extension /etc/nginx/sites-enabled/
sudo nginx -t
sudo systemctl restart nginx
sudo systemctl status nginx
```
