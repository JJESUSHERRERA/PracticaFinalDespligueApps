#JOSE DE JESUS HERRERA PADILLA 
#INSTITUTO TECNOLOGICO DE LEON
#LABORATORIO PARA EL DESPLIGUE DE APLICACIONES
FROM php:8.0.11-apache
RUN apt-get update
RUN docker-php-ext-install mysqli pdo pdo_mysql
#
COPY ./www.com /var/www/html

#Start services
CMD /usr/sbin/apache2ctl -D FOREGROUND

# Asignar el puerto
EXPOSE 80

