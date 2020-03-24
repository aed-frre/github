# Manejar archivos en repositorios

## Aclaración

Normalmente los archivos de un repositorio son manejados localmente en una PC a traves de la herramienta git y son subidos a discreción del programador al repositorio central. En Algoritmos y Estructura de Datos, manejar los archivos desde la interfaz web es suficiente para nuestros propósitos y por lo tanto no lo vamos a explicar, sin embargo estas invitado a seguir investigando y aprendiendo a usar esta plataforma

### Contenido

Aquí aprenderemos los siguiente

- [Crear archivos](#Crear-archivos)
- Subir archivos
- Eliminar archivos
- Crear carpetas
- Modificar archivos
- Ver historial de cambios

## Crear archivos

Cuando apenas hayamos creamos un nuevo repositorio, las siguientes opciones para agregar contenido al reposotorio aparecen

![Repositorio finalizado][fin-repo]

Para crear un nuevo archivo vacío hacemos click en *Create a New File*. La siguiente pantalla aparecerá

![Nuevo Archivo en Repositorio][nuevo-archivo]

Lo primero que debemos hacer es ponerle un nombre al archivo, en este caso `hola_mundo.psc`

> Es buena practica que los nombres de los archivos y de las carpetas en un repositorio no contengan espacios, para separar palabras se pueden usar guiones medios o guiones bajos ('-','\_')

> Como convensión vamos a utilizar la extensión de archivos `.psc` como extensión de los archivos que tienen Pseudocódigo.

Luego podemos ingresar el contenido que querramos al archivo.

Una vez que finalicemos de escribir en nuestro archivo debemos realizar un commit. Un commit es un punto en el tiempo de nuestro repositorio. Cualquier cambio por mas chico o grande que sea puede ser comiteado para futuras referencias. Luego vamos a poder navegar a traves de los commits de nuestro repositorio y observar los cambios que se realizaron entre cada uno de ellos.

Para realizar un commit de nuestro nuevo archivo lo que debemos hacer es en la parte inferior de la pantalla darle un título y un nombre al commit (puede dejarse los titulos y descripciones por defecto). Una vez que lo completamos hacemos click en *Commit New File*

![Archivo Modificado][archivo-modificado]

El nuevo archivo aparece en la raiz de nuestro repositorio. Si queremos seguir creando archivos podemos repetir los pasos anteriores haciendo click en *Create New File*
![Archivo Creado][archivo-creado]

Para ver el contenido del archivo solo hacemos click en el mismo.

![Archivo Creado][archivo-creado-2]

Podemos compartir nuestro algoritmo simplemente compartiendo la URL del mismo que se encuentra en la barra de direcciones.

## Subir archivos

## Eliminar archivos

## Crear carpetas

## Modificar archivos

## Ver historial de cambios

[fin-repo]: img/repo/fin-repo.png "Repositorio Finalizado"
[nuevo-archivo]: img/archivos/nuevo-archivo.png "Nuevo Archivo en Repositorio"
[archivo-modificado]: img/archivos/archivo-modificado.png "Archivo Modificado"
[archivo-creado]: img/archivos/archivo-creado.png "Archivo Creado"
[archivo-creado-2]: img/archivos/archivo-creado-2.png "Archivo Creado"
