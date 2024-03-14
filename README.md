# TFG-GLPi-Proyect
GLPI
GLPI es un Sistema desarrollado en Software Libre perteneciente a la categoría de «Software para Gestión de Servicios Informáticos (SGSI)», mayormente conocidos por su nombre en inglés «IT Service Management" (ITSM)». Un software «ITSM», por lo general, funciona como un sistema de tickets que abarca las actividades que son realizadas por una organización para entregar servicios y resolver problemas de TI con el mayor valor agregado posible para una mayor eficacia y eficiencia de los recursos manejados.

Es un sistema web que permite la administración (inventario) del parque informático (Equipos: servidores, ordenadores, periféricos, impresoras, multifuncionales, entre otros), y hasta del software usado en los servidores y ordenadores.

GLPI es una solución informática utilizada para el seguimiento de las incidencias tecnológicas en los departamentos de TI. Este software está creado con PHP, usa MySQL/MariaDB para la Base de datos gestionada, HTML en las páginas web, CSS en las hojas de estilo y XML para generar informes, y es distribuido bajo la licencia GNU/GPL versión 2.
Entre lo más destacable del mismo, es que al estar creado como Software Libre y/o Código Abierto, se puede ejecutar, modificar o desarrollar el código y redistribuirlo o compartirlo libremente. De este modo, sus creadores, contribuidores y usuarios pueden participar y beneficiarse del desarrollo progresivo de la misma, y de los módulos adicionales libres y de código abierto en sitios como GitHub

El propósito principal del uso de GLPI es facilitar el trabajo en la administración de soporte de y ticketing sin embargo en nuestro caso lo vamos a modificar para implementarle plugins y configuraciones para que agregar nuevas funciones para poder administrar y reportar equipos de forma remota donde mediante un script propio nos permitirá ver la ubicación del dispositivo en tiempo real, nombre del equipo y aplicaciones instaladas. Esto nos facilitara el soporte personalizado a clientes, podremos anticiparnos a muchos errores.
Nos permitirá crear y enviar informes del equipo tanto componentes como de sus fallos de forma remota además en caso de que la empresa pueda perder uno de los equipos por un traslado esta herramienta nos permite geo-localizarlo y decirle a cual de sus sucursales fue enviado. 
Solo con ejecutar el script podremos crear un mapeado de todos los dispositivos de la red y los podremos clasificar en una base de datos previamente configurada que reportara todos los datos a nuestra página web.


# References pages 

https://fusioninventory.org/

# Fusion-Inventory page for download version lists and configuration
https://github.com/fusioninventory/fusioninventory-for-glpi/releases

|- glpi
   |- plugins
      |- fusioninventory
         |- index.php
         |- hook.php
         |- inc
         |- ...
      
