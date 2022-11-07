# Tarea 3

Este repo se basa en el laboratorio de docker-compose que vimos anteriormente.

# Instrucciones

Haga un fork de este repo.
Siga los pasos y deje los resultados en su fork.

Esta tarea se puede hacer en grupos, cada grupo debe tener a lo más 5 integrantes.

En u-cursos hay una tarea, sube a la tarea un archivo con la url de la tarea y la lista de los integrantes del grupo.

Alternativamente, pueden hacer un pull request a este repo, incluyendo solamente el archivo README.md. En ese caso agregan los datos solicitados en la tabla que aparace debajo de **Entrega** al final de este documento.

# Paso 1

En este caso el docker-compose existe pero tiene algunos errores.
La tarea es corregirlo para que funcione, cuando lo tenga corregido haga un commit convencional de tipo `fix` y en el mensaje escriba que resolvió el paso 1 y arregló el problema con el docker-compose.

# Paso 2

Al levantar el docker-compose verá una versión extendida del programa de películas, esta vez hay un link que dice "Agregar Película", además cada película tiene un botón para editar.

Escriba un script en python para Selenium que agregue 2 películas y traduzca las descripciones de las películas Dune y Elvis.

Cuando termine haga un commit convencional de tipo `feat` agregando el script selenium.

Tips: 
- Si no tiene instalado Python usted puede ejecutar una imagen docker con python para correr su script
- Puede crear el script usando Selenium IDE y después lo modifica
- Basese en el ejercicio de docker-compose

# Entrega

docker-compose --env-file .env up -d

|grupo|integrantes|url del fork|
|-----|-----------|------------|
|Grupo Delta     |      Jocelyn Pardo - Andrea Calderon - Alejandra Levill - Omar Sosa - Jonathan Inostroza     |       https://github.com/mlevilll/Devops-2022-tarea-3.git     |






