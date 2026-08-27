# Respuestas Teóricas - Lab 03 DOSW

## Pregunta 1. What is a Maven Archetype?

Según la documentación oficial de Apache Maven:"Un archetype es un kit de herramientas para plantillas de proyectos Maven, definido como un patrón original o modelo a partir del cual se hacen todas las demás cosas del mismo tipo, con el objetivo de ofrecer un sistema que provea una forma consistente de generar proyectos Maven"

En nuestras palabras:
Es una plantilla para generar proyectos Maven, un patrón predefinido a partir del cual se puede crear rápidamente la estructura básica de un nuevo proyecto, con carpetas, archivos y un pom.xml ya configurados según un tipo de proyecto específico. 

## Pregunta 2. What is the purpose of the maven-archetype-quickstart archetype?

Es un arqueortipo oficial de Maven que se puede usar para generar un proyecto java simple y funcional desde cero. L aidea es que sirva como punto de partida mnimo para poder aprender a usar Maven o arrrancar proyectos sencillos en java.
Trae:
La estructura estandar un pom.xml inicial, unan clase App.java de ejemplo y una clase de prueba AppTest.java  


## Pregunta 3. What command can be used to create a project based on a Maven archetype?

El comando es 
**mvn archetype:generate**

Al ejecutar el comando, lo qu epasa es : 
1. Maven descarga el JAR  del arqueotipo que se le indique.
2. Dentro de ese JAR hay una "Plantilla" de archivos.
3. Maven toma esa plantilla y las combina con los datos que nosotros le dimos para generar archivos reales.
4. Se crea una carpeta nueva, que ya contiene la estructura de tu proyecto.

*"Es decir: el comando no crea la estructura desde cero por sí mismo — invoca al arquetipo, y es el arquetipo (la plantilla) el que define cómo se ve esa estructura." Claude sonnet 5.0*


## Pregunta 4.What is a pull request in GitHub?
Es una propuesta para fusionar (*merge*) cambios de codigo de una rama hacia otra. Funcipn de GitHub que me permite proponer mis cambios, en lugar de aplicarlos directamente a la rama principal, para que los demas colaboradores puedan revisarlos, comantarlos y discutirlos antes de que se integren al proyecto.
Los pull requests convierten un conjunto de cambios de código en una conversación.

## Pregunta 5. How do you create a pull request in GitHub?
Los pasos a seguir son:
1. Se crea una rama a partir d el rama principal *Main* y puedes hacer tus cambios ahí(localmente con Git, o directamente en GitHub).
2. Se suben los commits de esa rama al repositorio(*Push*).
3. En GitHub, vamos a lapestaña de pull request de tu repositorio.
4. Click en New pull request.
5. Se selecciona la rama base  y la rama de comparación.
6. Escribe el titulo y una descripción, explicando que cambiaste y por qué.
7. Clic en Create pull request


## Preguntas 6. How do you approve a pull request in GitHub?
Los pasos a seguir son:
1. En tu repositorio entra a la pestaña Pull requests.
2. De la lista haz clic en el pull request que quieres revisar.
3. Haz clic en la pestaña Files Changed para ver los cambuos propuestos
4. Revisa el codigo y si quieres puedes comentar líneas o archivos especificos.
5. Arriba del codigo modificado, haz clic en Review Changes
6. Escribe un comentario resumiento tu retroalimentacion.
7. Selecciona Approve.
8. Haz  clic en submit review






- [Referencias Usadas paar contestar](./referenciasUsadas.md)