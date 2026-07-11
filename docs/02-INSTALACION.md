# Instalación del servidor

## Docker

Versión:

29.6.1

## Docker Compose

v5.3.1

---

## Red Docker

Nombre

minegocio-net

Tipo

Bridge

---

## Contenedores

Portainer

Imagen:

portainer/portainer-ce:lts

Nombre:

minegocio-portainer

Puerto:

9443

---

MariaDB

Imagen

mariadb:11

Nombre

minegocio-mariadb

---

Dolibarr

Imagen

dolibarr/dolibarr:latest

Nombre

minegocio-erp

Puerto

8080

---

Nginx

Se utiliza como Reverse Proxy para:

minegocio.com.gt

erp.minegocio.com.gt

portainer.minegocio.com.gt

---

Cloudflare

DNS administrado mediante Cloudflare.

SSL activo.

---

Estado

Instalación completada correctamente.
