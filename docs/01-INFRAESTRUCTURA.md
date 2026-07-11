# Minegocio ERP
## Documento 01 - Infraestructura

**Proyecto:** Minegocio ERP

**Autor:** José Villeda

**Fecha de inicio:** 10 de julio de 2026

---

# Objetivo

Construir una plataforma ERP moderna para pequeñas y medianas empresas de Guatemala, basada en Dolibarr, utilizando Docker y una arquitectura modular que facilite futuras actualizaciones y el desarrollo de módulos propios.

---

# Servidor

Proveedor:
Oracle Cloud Always Free

Sistema Operativo:
Ubuntu Server 24.04 LTS

Arquitectura:
ARM64 (aarch64)

CPU:
2 vCPU

RAM:
12 GB

Disco:
200 GB SSD

Hostname:
minegocio

---

# Dominios

Dominio principal

https://minegocio.com.gt

ERP

https://erp.minegocio.com.gt

Administración

https://portainer.minegocio.com.gt

---

# Objetivos técnicos

- Docker como plataforma de contenedores.
- Portainer para administración.
- Nginx como Reverse Proxy.
- Certificados SSL con Let's Encrypt.
- Cloudflare como DNS y protección.
- MariaDB como motor de base de datos.
- Dolibarr como ERP base.
- Desarrollo propio mediante módulos.

---

# Arquitectura

Internet

↓

Cloudflare

↓

Nginx

↓

Docker

├── Portainer

├── Dolibarr

├── MariaDB

└── futuros servicios

---

# Estado actual

✔ Docker instalado

✔ Docker Compose instalado

✔ Red Docker minegocio-net creada

✔ Portainer funcionando

✔ MariaDB funcionando

✔ Dolibarr funcionando

✔ Nginx configurado

✔ Reverse Proxy operativo

✔ SSL operativo

✔ ERP accesible desde Internet

---

Versión del documento

0.1
