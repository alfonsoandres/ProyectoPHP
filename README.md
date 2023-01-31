# ProyectoPHP

Rama master 

1- Mostrar en detalles y en modificar la opción de siguiente y anterior--IMPLEMENTADO

2- Mostrar la lista de clientes con distintos modos de ordenación: nombre, apellido, correo electrónico, género o IP y poder navegar por ella.--NO IMPLEMENTADO

3- Mostrar en detalles una bandera del país asociado a la IP ( utilizar geoip y  https://flagpedia.net/ ) IMPLEMENTADO

4- Mejorar las operaciones de Nuevo y Modificar para que chequee que los datos son correctos:  correo electrónico (no repetido), IP y  teléfono con formato 999-999-9999.
IMPLEMENTADO

5- Mostrar una imagen asociada al cliente almacenada previamente en uploads o una imagen por defecto aleatoria generada por https://robohasp.org.  sin no existe. En nombre de las fotos tiene el formato 00000XXX.jpg para el cliente con id XXX.
IMPLEMENTADO

6-Permitir subir o cambiar la foto del cliente en modificar y en nuevo (La imagen no es obligatoria). Hay que controlar que el fichero subido sea una imagen jpg de un tamaño inferior a 1 Mbps. 
NO IMPLEMENTADO

7-Generar un PDF con los todos detalles de un cliente ( Incluir un botón que indique imprimir)
IMPLEMENTADO

8-Crear una nueva tabla en la BD de usuarios de la aplicación (User)  con tres campos: login, password( encriptada )  y rol (0/1), definir varios usuarios y controlar el acceso a la aplicación sólo si se introduce el login y el password correctos. Si se realizan más de tres intentos erróneos se solicitará que se reinicie el navegador.
NO IMPLEMENTADO

9-Controlar el acceso a la aplicación en función del rol, si es 0 solo puede acceder a visualizar los datos: lista y detalles. Si el rol es 1 podrá además modificar, borrar y eliminar usuarios.
NO IMPLEMENTADO

10- Utilizar geoip y el api para javascript https://openlayers.org o similar para mostrar la localización geográfica del cliente  en un mapa en función de su IP.
NO IMPLEMENTADO
