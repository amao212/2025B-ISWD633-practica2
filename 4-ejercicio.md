## Esquema para el ejercicio
![Imagen](esquema-4-ejercicio.PNG)

### Crear la red
# COMPLETAR

### Crear el contenedor mysql a partir de la imagen mysql:8, configurar las variables de entorno necesarias
# COMPLETAR

### Crear el contenedor wordpress a partir de la imagen: wordpress, configurar las variables de entorno necesarias
# COMPLETAR

De acuerdo con el trabajo realizado, en el esquema del ejercicio el puerto a es **(8080)**

Ingresar desde el navegador al wordpress y finalizar la configuración de instalación.
# COLOCAR UNA CAPTURA DE LA CONFIGURACIÓN

<img width="1667" height="1296" alt="image" src="https://github.com/user-attachments/assets/44bf6296-2c17-48c0-910f-1089d1edb609" />

<img width="1402" height="960" alt="image" src="https://github.com/user-attachments/assets/78382338-241d-49bc-add9-94b2332c1120" />

<img width="1308" height="652" alt="image" src="https://github.com/user-attachments/assets/8f3aeba7-7f99-4a59-89c3-0d0d278ca1ab" />


Desde el panel de admin: cambiar el tema y crear una nueva publicación.
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress
# COLOCAR UNA CAPTURA DEL SITO EN DONDE SEA VISIBLE LA PUBLICACIÓN.

<img width="1911" height="972" alt="image" src="https://github.com/user-attachments/assets/d9b3dfdb-9fce-4e3e-9e4b-d791bd78abfe" />


### Eliminar el contenedor wordpress
# COMPLETAR

### Crear nuevamente el contenedor wordpress
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress

### ¿Qué ha sucedido, qué puede observar?
# COMPLETAR

Al eliminar y volver a crear el contenedor de wordpress e ingresar a la página, esta esta en blanco, posiblemente debido a algunos archivos que quedaron de la anterior instalación.

