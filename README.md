# Manual-Nextcloud

Para cada proyecto de vagrant crea una carpeta y llamala como quieras para trabajar con Ubuntu 22.04 Jammy Jellyfish.

dentro de la carpeta haz

``` 
vagrant init ubuntu/jammy64:
Para crear el fichero de Vagrant

ll

vagrant up --provider=virtualbox:
Para levantar la infraestructura

vagrant ssh:
Asi iniciamos sesion con la clave del host

ll /vagrant
```

Despues de hacer estos comandos no se habra guardado en la maquina asi que hacemos un "apt update" o un "apt upgrade", Con la maquina ya actualizada he instalado estos servidores web con los siguientes comandos:

```
sudo apt install -y apache2

sudo apt install -y mysql-server

sudo apt install -y php libapache2-mod-php

sudo apt install -y php-fpm php-common php-mbstring php-xmlrpc php-soap php-gd php-xml php-intl php-mysql php-cli php-ldap php-zip php-curl
```


