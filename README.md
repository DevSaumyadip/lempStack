# lempStack
docker composer for LEMP staack on PRI 64

# download phpMyAdmin zip file and unzip to public_html and create tmp on root
https://files.phpmyadmin.net/phpMyAdmin/5.0.2/phpMyAdmin-5.0.2-english.zip

# install sqldriver on php-fpm
docker-php-ext-install mysqli

# and restart nginx

# then replace lempStack/public_html/phpMyAdmin/libraries line with $cfg['Servers'][$i]['host'] = 'mql server url';

# /public_html/phpMyAdmin# chmod 777 tmp/