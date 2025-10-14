# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.


Consultar: Cómo se gestionan datos confidenciales con los secretos de Docker (Docker Secrets).

Un secreto es un objeto cifrado que Docker mantiene de forma segura, sirve para guardar datos sensibles que no deben incluirse en imágenes, variables de entorno o archivos de configuración expuestos.

Los secretos se almacenan cifrados en el manager node un clúster Swarm (conjunto de máquinas (nodos) que trabajan como un solo sistema).

Cuando se asigna un secreto a un servicio, Docker lo monta temporalmente como un archivo de memoria (tmpfs) dentro del contenedor.

Solo los contenedores autorizados pueden acceder a ese secreto.

Cuando el contenedor se deteniene, el secreto se elimina automáticamente.



docker run -d --name mi_postgres -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=12345 -e POSTGRES_DB=postgres -p 5432:5432 postgres:15-alpine3.21


docker run -d --name mi_pgadmin -e PGADMIN_DEFAULT_EMAIL=admin@admin.com -e PGADMIN_DEFAULT_PASSWORD=admin -p 5050:80 dpage/pgadmin4


docker exec -it mi_postgres psql -U postgres


CREATE DATABASE info;

\c info

CREATE TABLE personas(
info(# id SERIAL PRIMARY KEY,
info(# nombre VARCHAR(100)
info(# );

INSERT INTO personas (nombre) VALUES ('Angel Anguaya'), ('Maria Perez');





