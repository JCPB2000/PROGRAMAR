# para dar permisos 
```
sudo chown -R ubuntu:ubuntu /var/www/html
```

# PARA CREAR EL DNS
```
sudo nano /etc/apache2/sites-available/losvencedores3tespe.com.conf
```
```
<VirtualHost *:80>
    ServerAdmin webmaster@losvencedores3tespe.com
    ServerName losvencedores3tespe.com
    ServerAlias www.losvencedores3tespe.com
    DocumentRoot /var/www/html
    ErrorLog ${APACHE_LOG_DIR}/error.log
    CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>

```

CTR O  PARA guardar
CTR x para salir

para habilitar
sudo a2ensite losvencedores3tespe.com.conf
```