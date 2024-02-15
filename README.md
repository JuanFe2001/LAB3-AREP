## Escuela Colombiana de Ingeniería
### Arquitecturas Empresariales – AREP
# LAB3-AREP
#### TALLER 3: MICROFRAMEWORK WEB
En este taller usted debe explorar la arquitectura del microframework WEB denominado sparkweb (https://sparkjava.com/). Este micro framework permite construir aplicaciones web de manera simple usando funciones lambda.
Para este ejercicio usted deb construir un  servidor web para soportar una funcionalidad similar a la de Spark. Su aplicación debe permitir por lo menos el registro de servicios get y post usando funciones lambda. Implemente igualmente funciones que le permitan configurar el directorio de los archivos estáticos, y otra que permita cambiar el tipo de la respuesta a "application/json". Para esto solo debe usar el API básico de Java. No utilice frameworks como Spark o Spring.
## Elementos necesarios 
Para poder ejecutar o correr el proyecto se necesitan unos requisitos minimos los cuales son:
* [Tener Instalado Maven](https://maven.apache.org/download.cgi)
* [Git](https://git-scm.com/downloads)
* [Tener una version de Java 17 o mas](https://www.oracle.com/co/java/technologies/downloads/)
## La aplicacion cuenta con 4 clases las cuales son

**MovieServer**: La clase actúa como servidor para una aplicación web de consulta de información de películas.

**APIRestMovies**: Actúa como interfaz para realizar solicitudes a una API REST que proporciona información sobre películas.

**Cache**: Gestiona una caché de información de películas utilizando un ConcurrentHashMap.

**Main**: Tiene como propósito general iniciar la aplicación del servidor de películas.

## Adicionalmente
Se añadieron archivos css, js y html, el servidor retorna estos archivos como lo veremos a continuacion

## POR CONSOLA
Por consola nos metemos hasta la carpeta Lab1 del proyecto y desde ahi ponemos los siguientes comandos

* mvn clean compile
* mvn exec:java
  
El primer comando nos ayudara a compilar el proyecto y el segundo a ejecutarlo

## DIRECTAMENTE DEL IDLE
Si queremos ejecutarlo de la otra forma solo tenemos que correr la clase Main con ayuda de nuestro IDLE

## NOTA:
En los dos casos lo mas recomendable para ver el funcionamiento de la pagina es utilizar el Navegador de FireFox

## DEMOSTRACION
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/66930ab4-f1ba-4041-9616-8b37dfa045da)
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/70029c6b-6e25-4f9b-bd34-2b13720d9fd5)
Con la ruta http://localhost:35000/service/prueba1?message=Juan%20Felipe podemos probarlo donde en message =
podemos poner la frase que queramos
Prueba1
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/0783021a-a3e8-489a-8963-b39c2be5d2c3)
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/e5bb3abf-2d70-4952-aaec-15d0e645a365)
http://localhost:35000/service/prueba2?message=Leer
Prueba2
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/0e84f0f5-c73f-445d-9362-07c5997e6edc)
![image](https://github.com/JuanFe2001/LAB3-AREP/assets/123691538/6f7d8c43-3753-4d57-8f84-7b0d4f324dbb)
Cuando no encuentra el recurso vemos que sale error 404 en la peticion
Prueba 3
# Generar el JavaDoc
Para Generar el JavaDoc en la consola en la carpeta Lab1 por consola ponemos el siguiente comando

* mvn site

## Autor
* Juan Felipe Vivas Manrique
