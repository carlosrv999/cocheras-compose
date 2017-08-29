Pasos para instalar la app (requisitos: tener Docker y Docker Compose instalados):

1: Clonar este repositorio
 - git clone https://github.com/carlosrv999/cocheras-compose.git
2: Cambiar al directorio:
 - cd cocheras-compose
3: Clonar los proyectos front, backend y bd (con los nombres indicados abajo!):
 - git clone https://github.com/carlosrv999/cocheras-db.git db
 - git clone https://github.com/carlosrv999/cocheras.git cocheras-lb
 - git clone https://gitlab.com/carlosrv999/cocheras-front.git cocheras-front
4: Ejecutar el proyecto con el comando:
 - docker-compose up (requiere permisos de admin)