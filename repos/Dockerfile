FROM httpd:2.4

COPY httpd.conf /usr/local/apache2/conf/httpd.conf
COPY httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf

ADD em /var/www/em
ADD m2e /var/www/m2e
ADD liferay-ide-osgi-deps /var/www/liferay-ide-osgi-deps
