# Variables de Entorno
### ¿Qué son las variables de entorno?

Las variables de entorno son pares clave-valor que forma parte del sistema donde se esta ejecutando el proceso, proporcionan información al sistema o aplicaciones sobre 
configuraciones específicas.

# COMPLETAR

### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.

# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR

<img width="1079" height="77" alt="image" src="https://github.com/user-attachments/assets/106de995-36b9-4af1-ac4a-b6cff794dbf1" />

<img width="488" height="47" alt="image" src="https://github.com/user-attachments/assets/d042c433-d915-48cd-98d9-decb36457c1c" />


<img width="927" height="648" alt="image" src="https://github.com/user-attachments/assets/8db6951e-5b9f-4076-a8f8-3653b8bcf906" />



### Crear un contenedor con la imagen de mysql, mapear todos los puertos
# COMPLETAR

### ¿El contenedor se está ejecutando?

no

# COMPLETAR

### Identificar el problema
# COMPLETAR

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

### Crear un contenedor con mysql, mapear todos los puertos y configurar las variables de entorno mediante un archivo
# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR 

### ¿Qué bases de datos existen en el contenedor creado?
# COMPLETAR
