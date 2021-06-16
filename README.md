# olqs/php
Image build on top off the official php 8-fpm container
## Added php modules
* pdo_pgsql
* mysqli
* gd
* imagick
* exif
* zip

Caution: Imagick is compiled from source from the master branch, not fully working

## Added software
* msmtp linked to /usr/bin/sendmail, configuration file /etc/msmtprc not included, see https://marlam.de/msmtp/documentation/ for details


For usage infomation please go to https://hub.docker.com/_/php 
