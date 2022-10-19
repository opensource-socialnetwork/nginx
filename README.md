# OSSN NGINX
A experimental config for ngnix users.  You can run OSSN on nginx but we don't provide support for NGINX.  

1. Copy ossn.conf to /etc/nginx/sites-available/
2. Load the ossn.conf sudo ln -s /etc/nginx/sites-available/ossn.conf /etc/nginx/sites-enabled/
3. Edit ossn.conf change the server name to your domain name
4. Edit the fastcgi_pass with your php-fpm sock path  Make sure you have php-fpm installed.


