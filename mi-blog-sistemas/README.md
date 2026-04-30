# Proyecto ASIR - Servidor Web Apache en Ubuntu

## Descripción

Este proyecto consiste en el desarrollo y despliegue de una página web utilizando Astro como frontend y PHP junto con MariaDB como backend, implementado en un servidor Apache sobre Ubuntu Server en una máquina virtual.

El objetivo principal es simular un entorno real de publicación web, abarcando no solo el desarrollo de la aplicación, sino también la configuración del servidor, la seguridad y la monitorización del sistema.


## Tecnologías utilizadas

* Astro (Frontend)
* HTML, CSS y JavaScript
* PHP (Backend)
* MariaDB (Base de datos)
* Apache (Servidor web)
* Ubuntu Server (Sistema operativo)
* XAMPP


## Funcionalidades principales

* Navegación web mediante contenido estático generado con Astro.
* Formulario de contacto con envío de datos al servidor.
* Almacenamiento de datos en base de datos MariaDB.
* Consumo de API externa (GNews) para mostrar noticias dinámicas.
* Implementación de modo oscuro en la interfaz.


## Despliegue

La aplicación se ha desplegado en un servidor Apache dentro de un entorno Ubuntu virtualizado.

El proceso de despliegue consiste en:

1. Generar el build del proyecto Astro:
   npm run build

2. Copiar los archivos generados en la carpeta `dist` al directorio:
   /opt/lampp/htdocs

3. Acceder a la web mediante la dirección IP del servidor desde un navegador.


## Limitaciones

La versión incluida en este repositorio puede ejecutarse como contenido estático. Las funcionalidades dinámicas (procesamiento en PHP, conexión con base de datos y consumo de API externa) requieren un entorno servidor configurado con Apache, PHP y MariaDB.

