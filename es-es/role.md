# Nivel de autorización de usuarios

La jerarquía de usuarios está estrictamente definida, sin posibilidad de hacer excepciones.
dinoRemote puede configurarse con varios tipos de usuarios y funciones.


A continuación se indica la estructura y distribución de funciones de dinoRemote.

+ En primer lugar está el equipo. Éste sólo puede tener un propietario. 
+ Al propietario del equipo se le asigna un único distribuidor.  
Un distribuidor puede atender a distintos propietarios. 
+ El propietario tiene acceso únicamente a un equipo, mientras el distribuidor tiene acceso a los equipos de todos los propietarios bajo su tutela. 
+ Por motivos de protección de datos es imprescindible que los propietarios de los equipos autoricen el mantenimiento a distancia de los mismos. En caso contrario, el distribuidor o dinotec sólo podrá tener acceso a conocer si el equipo está en funcionamiento o detenido, todos los demás datos están bloqueados. 

Ejemplo de estructura:

![imagen alt texto](../assets/role.png)
