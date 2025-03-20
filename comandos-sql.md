## Ejercicio 1: Muestra todas las variables del sistema disponibles en MySQL.

`SHOW VARIABLES;`

![alt text](Ejercicio_1.png)

## Ejercicio 2: Muestra todas las variables del sistema que contengan la palabra size.

`SHOW VARIABLES LIKE '%size%';`

![alt text](Ejercicio_2.png)

## Ejercicio 3: Encuentra todas las variables del sistema cuyo nombre comience con la palabra innodb.

`SHOW VARIABLES LIKE 'innodb%';`

![alt text](Ejercicio_3.png)

## Ejercicio 4: Encuentra todas las variables del sistema cuyo nombre termine con timeout.

`SHOW VARIABLES LIKE '%timeout';`

![alt text](Ejercicio_4.png)

## Ejercicio 5: Muestra el valor exacto de la variable max_allowed_packet.

`SHOW VARIABLES LIKE 'max_allowed_packet';`

![alt text](Ejercicio_5.png)

## Ejercicio 6: Muestra el valor exacto de la variable bind-address.

`SHOW VARIABLES LIKE 'bind_address';`

![alt text](Ejercicio_6.png)

## Ejercicio 7: Encuentra todas las variables que tengan la palabra buffer en cualquier parte del nombre.

`SHOW VARIABLES LIKE '%buffer%';`

![alt text](Ejercicio_7.png)

## Ejercicio 8: Muestra todas las variables que contengan la palabra dir.

`SHOW VARIABLES LIKE '%dir%';`

![alt text](Ejercicio_8.png)

## Ejercicio 9: Cargar el fichero `tienda-productos.sql` en Base de Datos. Para ello utiliza el comando SOURCE con rutas relativas.

`SOURCE tienda-productos.sql;`

![alt text](Ejercicio_9.png)

## Ejercicio 10: Cargar el fichero `tienda-clientes.sql` en Base de Datos. Para ello utiliza el comando SOURCE con rutas absolutas.

`SOURCE /home/alumno/tienda-clientes.sql;`

![alt text](Ejercicio_10.png)