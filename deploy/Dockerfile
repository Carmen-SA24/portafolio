# Archivo donde especificque la instalacion de librerias y configuraciones a la 
# 1-.partimos de una imagen de Dcoker con apache instalado
# FROM ubuntu + instalacion personal de Apache
FROM httpd:2.4
# debemos consultar el docker hub (imagen) para ver variables de entorno directorios de trabajo etc etc
# Directorio de trabajo dentro del contenedor
WORKDIR /usr/local/apache2/htdocs
COPY ../src .
EXPOSE 80