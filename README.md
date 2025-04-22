Github para Proyecto 2 del Master de Ciberseguridad de Stucom
-Kelvin

Creado un Ubuntu server en Proxmox local de casa.

1000- Proyecto2

  ip: 192.168.1.160
  
  Stucom.2024
  


Instalado en la maquina del Proyecto2:

  -SSH.SERVER: para conexion remota por MobaXTerm
  -Docker: para crear los containers necesario con todas las herramientas
  
    -Portainer: para ver visualmente todos los otros contenedores.
    -Apache PHP 8.2: donde estara la pagina html.
      -Falta instalar mysqli ya que no funciona correctamente la parte de conexion a mysql. (12/04/2025)
    -MYSQL para mantener la base de datos para la pagina web hosteada en el apache.
    -Phpmyadmin para administrar visualmente la parte de mysql.
    ---Necesario para checkear el codigo---
    -SonarQube: Analisis estatico del codigo de la pagina.
    -Jenkins: Automatizacion de codigo abierto
    
  
