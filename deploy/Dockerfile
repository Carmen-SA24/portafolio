# Partimos de una iamgen bash de ubuntu donde instalaremos apache . configuraremos y arrancaremos
FROM ubuntu
RUN apt update && apt install -yq --no-install-recommends \ apache2 \ nano \ curl \ net-tools iputils-ping

# debemos consultar el docker hub (imagen) para ver variables de entorno directorios de trabajo etc etc
# Directorio de trabajo dentro del contenedor
WORKDIR /var/www/html
# El directorio . es relativo  al contexto del docker
COPY ./src .
EXPOSE 80
CMD apachectl -DFOREGROUND