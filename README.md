# DOSW_Lab3_Sua_Ortiz_Duarte


## Parte 1 - Estructura del Proyecto

#### 1. ¿Qué es un arquetipo de Maven?

Un arquetipo de Maven es un modelo original donde se desarrollan todas
aquellas cosas que son del mismo tipo. Donde los programadores utilizan plantillas
como base para utilizar ciertas tecnologías para escribir y organizar el código
de la aplicación.

#### 2. ¿Cuál es el propósito del arquetipo? `maven-archetype-quickstart`
Proporcionar una plantilla que permita crear proyectos de forma sencilla
para que los usuarios puedan familiarizarse con el uso de Maven y trabajen
con buenas prácticas.

#### 3. ¿Qué comando se puede utilizar para crear un proyecto basado en un arquetipo de Maven?
R/ Para crear un proyecto con un arquetipo de Maven, se utiliza el comando mvn archetype:generate como el mencinado en la plantilla dada en el enunciado (mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5).Al ejecutarlo de forma interactiva, el sistema solicita seleccionar un arquetipo y definir las coordenadas del proyecto

#### 4. ¿Qué es una pull request en GitHub?
R/ Una Pull Reques en GitHub es una solicitud que realiza un desarrollador para fusionar usando merge los cambios de un código alojado en una rama o fork hacia una rama main o develop, ademas facilita la revisión de código con comentarios y ajustes colaborativos, integran pruebas CI/CD para ver que los cambios no rompan el proyecto actual y por ultimo ofrecen control de calidad y trazabilidad al mantener un registro centrado en discusiones, aprobaciones y modificaciones.

#### 5. Como crear un pull request en Github?
Para crear un pr vamos a la aplicación de Github, abrimos el repositorio y debajo del boton verde
 code hacemos click en el boton pull request, saldra una ventana llamada "Open a pull request" donde
  devemos proveer detalles necesarios de lo que hemos hecho, luego le damos en el boton create pull request
#### 6. Como aprobar un pull request en Github?
    para aprobarlo vamos a la aplicación de Github, abrimos el pull request en el repositorio, damos click
     en revisar cambios, redactamos un mensaje breve, seleccionamos la casilla aprobar y enviamos la revision
    

#### Comando utilizado para crear la estructura del proyecto

```bash
mvn archetype:generate -DgroupId=edu.eci.dosw.lab -DartifactId=DOSW-Laboratorio3 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false
```

#### Bibliografía

*Pregunta 1*
Adictos al trabajo. (2008, 9 de junio). Arquetipos de Maven: Cómo crear, distribuir y generar proyectos con JSF e ICEfaces, JBoss y EJB3. 
https://adictosaltrabajo.com/2008/06/09/creararquetiposmaven/

*Pregunta 2*
Apache Maven Project. (s. f.). Introduction to archetypes. 
https://maven.apache.org/guides/introduction/introduction-to-archetypes.html

*Pregunta 3*
Cardellino, F. (2021, 26 de enero). Cómo hacer tu primer pull request en GitHub. freeCodeCamp.
https://www.freecodecamp.org/espanol/news/como-hacer-tu-primer-pull-request-en-github/

*Pregunta 4*
Aprende GIT. (2013, 14 de febrero). ¿Qué es un pull request? Aprende GIT 
https://aprendegit.com/que-es-un-pull-request/


*Pregunta 5*
Apache Software Foundation. (s. f.). Maven Archetype Plugin – archetype:generate. Apache Maven Project.
https://maven.apache.org/archetypes/user-guide.html

*Pregunta 6*
GitHub. (s. f.). About pull requests. GitHub Docs.
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
