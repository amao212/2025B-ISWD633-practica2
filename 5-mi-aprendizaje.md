# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Los conocimientos obtenidos en primer lugar las variables de entorno, esto ayudo mas en la parte de base de datos debido a que se debian configurar el usuario root, otro usuario, correo y contraseña, depende de la base de dato y la documentación de docker hub.

Luego, aprendi como conectar un contenedor postgres y un cliente, par poder crear una base de datos, luego en la parte de redes aprendí a crear reder de tipo bridge, con la cual puedo asociar a los contenedores y ya no tendria que exponer los puertos, solo se expondria los puertos de host y contenedor.

En el ultimo ejercio se tuvo que crear una red para poner un contenedor mysql y conectarlo con un contenedor wordpress la cual se hizo correctamente, hubo algunos problemas al poner la base de datos pero al ultimo se soluciono.


Consultar: Cómo se gestionan datos confidenciales con los secretos de Docker (Docker Secrets).

Un secreto es un objeto cifrado que Docker mantiene de forma segura, sirve para guardar datos sensibles que no deben incluirse en imágenes, variables de entorno o archivos de configuración expuestos.

Los secretos se almacenan cifrados en el manager node un clúster Swarm (conjunto de máquinas (nodos) que trabajan como un solo sistema).

Cuando se asigna un secreto a un servicio, Docker lo monta temporalmente como un archivo de memoria (tmpfs) dentro del contenedor.

Solo los contenedores autorizados pueden acceder a ese secreto.

Cuando el contenedor se deteniene, el secreto se elimina automáticamente.












