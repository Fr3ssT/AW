## INSTALAR EN UBUNTU 18.04 UN APACHE

## Introducción Servidor Apache


$ sudo apt install apache2

sudo fuser -vki /var/lib/dkpg/lock

![Imagen](/)

### Firewall 
$ sudo ufw app list

### Procesos
$ ps -all
Para ver los procesos que se están ejecutando

### Iniciar el servicio de Apache
$ sudo systemctl start apache2

### Ver el estado del servicio de Apache
$ sudo systemctl status apache2

### Monitorizar pagina web
$ curl

### Ver las ip del equipo
$ hostname -I

### Instalar 2 dominios en una misma Máquina Ubuntu
sudo mkdir -p /var/www/example.com/public.html

sudo mkdir -p /var/www/test.com/public.html

sudo nano index.html en cada apartado que hemos creado, ya que estás serán sus páginas web

sudo cp /etc/apache2/sites-available/ooo-default.conf /etc/apache2/sites-available/example.com.conf

cd /etc/apache2/sites-available 

nano example.com.conf


