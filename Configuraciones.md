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

# Resumen de Comandos
Comando	Descripción
```
df -h	# Ver espacio total y disponible en disco.
du -h --max-depth=1 /	#Ver cuánto ocupa cada carpeta.
lsblk	#Ver discos y particiones conectadas.
sudo fdisk -l	#Información detallada de discos y particiones.
find / -type f -size +100M	#Encontrar archivos grandes en el servidor.
```