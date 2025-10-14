### Crear contenedor de Postgres sin que exponga los puertos. Usar la imagen: postgres:15-alpine3.21
# COMPLETAR

### Crear un cliente de postgres. Usar la imagen: dpage/pgadmin4

# COMPLETAR

La figura presenta el esquema creado en donde los puertos son:
- a: puerto pgAdmin en host 5050
- b: puerto interno pgAdmin 80
- c: puerto de PostgresSQL(host y contenedor) 5432

![Imagen](esquema-2-ejercicio.PNG)

## Desde el cliente
### Acceder desde el cliente al servidor postgres creado.
# COMPLETAR CON UNA CAPTURA DEL LOGIN

<img width="669" height="494" alt="image" src="https://github.com/user-attachments/assets/29cc1bbd-92a6-425f-9651-18efda0d2298" />

<img width="1913" height="910" alt="image" src="https://github.com/user-attachments/assets/1f5c7950-a214-4853-a9ae-69c3d718b59e" />


### Crear la base de datos info, y dentro de esa base la tabla personas, con id (serial) y nombre (varchar), agregar un par de registros en la tabla, obligatorio incluir su nombre.

## Desde el servidor postgresl
### Acceder al servidor
### Conectarse a la base de datos info
# COMPLETAR
### Realizar un select *from personas
# AGREGAR UNA CAPTURA DE PANTALLA DEL RESULTADO


<img width="1899" height="1367" alt="image" src="https://github.com/user-attachments/assets/a8c28ed4-79ba-44af-b510-fbbaad762145" />

<img width="397" height="238" alt="image" src="https://github.com/user-attachments/assets/1f9e987a-dfaa-49b5-9596-3ca58670ecae" />
