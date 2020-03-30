# Manejar archivos en repositorios

## Aclaración

Normalmente los archivos de un repositorio son manejados localmente en una PC a traves de la herramienta git y son subidos a discreción del programador al repositorio central. En Algoritmos y Estructura de Datos, manejar los archivos desde la interfaz web es suficiente para nuestros propósitos y por lo tanto no lo vamos a explicar, sin embargo estas invitado a seguir investigando y aprendiendo a usar esta plataforma

### Contenido

Aquí aprenderemos los siguiente

- [Crear archivos](#Crear-archivos)
- [Subir archivos](#subir-archivos)
- [Eliminar archivos](#eliminar-archivos)
- [Crear carpetas](#crear-carpetas)
- [Modificar archivos](#modificar-archivos)
- [Ver historial de cambios](#ver-historial-de-cambios)

## Crear archivos

Para crear un nuevo archivo vacío luego de haber creado nuestro repositorio hacemos click en *Create a New File*. 

![image](img/1.png)

El siguiente espacio aparecerá

![image](img/2.png)

Lo primero que debemos hacer es decidir un nombre para el archivo, en este caso `hola_mundo.psc`

> Es buena practica que los nombres de los archivos y de las carpetas en un repositorio no contengan espacios, para separar palabras se pueden usar guiones medios o guiones bajos ('-','\_')

> Como convensión vamos a utilizar la extensión de archivos `.psc` como extensión de los archivos que tienen Pseudocódigo.

Luego podemos ingresar el contenido que querramos al archivo.

![image](img/3.png)

Una vez que finalicemos de escribir en nuestro archivo debemos realizar un commit. Un commit es un punto en el tiempo de nuestro repositorio. Cualquier cambio por mas chico o grande que sea puede ser comiteado para futuras referencias. Luego vamos a poder navegar a traves de los commits de nuestro repositorio y observar los cambios que se realizaron entre cada uno de ellos.

Para realizar un commit de nuestro nuevo archivo lo que debemos hacer es en la parte inferior de la pantalla darle un título y un nombre al commit (puede dejarse los titulos y descripciones por defecto). Una vez que lo completamos hacemos click en *Commit New File*

![image](img/4.png)

El nuevo archivo aparece en la raiz de nuestro repositorio. Si queremos seguir creando archivos podemos repetir los pasos anteriores haciendo click en *Create New File*

![image](img/5.png)

Para ver el contenido del archivo solo hacemos click en cualquier archivo en nuestro repositorio.

![image](img/6.png)

Podemos compartir nuestro algoritmo simplemente compartiendo la URL del mismo que se encuentra en la barra de direcciones.

![image](img/7.png)

## Subir archivos

De manera similar, en lugar de editar los archivos por la interfaz web se pueden subir archivos directamente hacia el repositorio. Esto se logra haciendo click en *Upload files* dentro de la carpeta en repositorio que quisieramos subir el archivo. 

![image](img/8.png)

![image](img/9.png)

Se seleccionan o arrastran los archivos a subir y similar que en la creación de archivos se escribe un título y una descripcion al commit. 

Una vez finalizado hacemos click en *Commit Changes*

![image](img/10.png)

Este proceso se puede repetir con los mismos archivos cuantas veces se desee, los cambios entre archivos son inferidos por GitHub y guardados en el historial de cambios.

## Eliminar archivos

Para eliminar archivos simplemente lo que hacemos es abrir el archivo en cuestión y hacemos click en el icono de la basura *Delete this file*

![image](img/11.png)

Como la eliminación de un archivo tambien implica un cambio en el repositorio tiene que ser commiteado. Ingresamos un título y descripción para el commit y hacemos click en *Commit Changes*

![image](img/12.png)

## Crear carpetas

En un repositorio git no pueden existir carpetas vacías, de manera que para poder crear una carpeta tenemos que crear el archivo que va a ir dentro de la misma.

De la misma forma que haciamos para crear un archivo, hacemos click en *Create a New File*. Luego en el nombre del archivo se antepone el nombre de la carpeta y se finaliza con un simbolo "/". Se pueden crear varias carpetas anidadas si es neceario, separando sus nombres con el simbolo "/".

![image](img/13.png)

Escribimos un nombre y una descripcion para registrar nuestro cambio en un commit y hacemos click en *Commit New File*

## Modificar archivos

Para modificar un archivo lo que tenemos que hacer es hacer click en el icono en forma de lapiz *Edit this File*.

![image](img/14.png)

Procedemos a realizar todos los cambios necesarios y realizamos el commit de los mismos poniendo un título y una descripción al fondo de la pagina y luego haciendo click en *Commit Changes*

![image](img/17.png)

## Ver historial de cambios

Para poder ver todos los cambios que hemos commiteado lo que tenemos que hacer click en *Commits* estando situado en la raiz del repositorio.

![image](img/15.png)

Si hacemos click en cada uno vamos a poder ver las diferencias ingresadas en el repositorio por ese commit.

![image](img/16.png)

![image](img/18.png)

## Listo

Hemos aprendido a manipular archivos desde la interfaz web de GitHub. Para finalizar vamos a aprender sobre los [Pull Request](pull-request.md).

