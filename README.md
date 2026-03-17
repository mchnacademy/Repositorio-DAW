# Pautas exposicion Git:

---

## Contenido del repositorio

Para empezar, voy a explicar cómo hemos trabajado con Git desde cero, es decir, desde la creación del repositorio hasta la subida de proyectos.

Lo primero que necesitamos es tener una cuenta en GitHub, ya que es la plataforma donde vamos a almacenar nuestro repositorio. Además, también es necesario instalar dos herramientas: Git Bash, que nos permite introducir comandos, y Git GUI, que ofrece una interfaz más visual.

Una vez tenemos todo instalado, el siguiente paso es crear el repositorio. Para ello, dentro de GitHub, en la parte superior izquierda, encontramos un botón que nos permite crear un nuevo repositorio. Ahí es donde se guardará todo nuestro trabajo.

Cuando el repositorio ya está creado, tenemos dos formas de empezar a trabajar. La más habitual es clonarlo en nuestro ordenador. Esto se hace con el comando git clone seguido de la URL del repositorio. Por ejemplo, usaríamos git clone y el enlace del repositorio. Esto nos descarga todo el contenido y nos permite trabajar en local.

Otra opción es crear un repositorio directamente desde Git Bash usando el comando git init. Este comando crea una carpeta oculta llamada .git, que es donde se guarda toda la información del control de versiones.

A partir de aquí empezamos con la parte más importante, que es cómo organizar y subir nuestros proyectos.

Cuando entramos por primera vez al repositorio, estamos en la rama principal, llamada main. En esta rama normalmente solo dejamos el archivo README.md, que sirve para explicar el contenido del repositorio.

Para trabajar de forma organizada, lo recomendable es no trabajar directamente en main, sino crear nuevas ramas, también llamadas branches. Para crear una rama usamos el comando git branch seguido del nombre de la rama. Después, para movernos a esa rama usamos git checkout.

También existe una forma más rápida, que es usar git checkout -b seguido del nombre, que crea la rama y nos cambia automáticamente a ella.

Para comprobar en qué rama estamos en cada momento, utilizamos el comando git branch, que nos muestra todas las ramas y marca la actual.

Una vez dentro de la rama correcta, ya podemos empezar a añadir archivos. Para ello usamos el comando git add seguido del nombre del archivo. Si queremos añadir todos los archivos de golpe, podemos usar git add punto. Pero hay que tener cuidado, porque solo añadirá los archivos que estén dentro de la carpeta del repositorio.

Si cometemos un error al añadir archivos, podemos deshacerlo con el comando git reset, ya sea indicando un archivo concreto o aplicándolo a todos.

Después de añadir los archivos, el siguiente paso es confirmar los cambios. Esto se hace con git commit -m, donde escribimos un mensaje explicando qué hemos añadido o modificado. Este mensaje es importante porque nos permite entender el historial de cambios.

Finalmente, para subir los cambios al repositorio remoto en GitHub, usamos el comando git push. Si es la primera vez que subimos esa rama, usamos git push -u origin seguido del nombre de la rama. Si ya la habíamos subido antes, simplemente usamos git push.

Para terminar, me gustaría explicar brevemente la estructura de nuestro repositorio. Nosotros hemos organizado el trabajo utilizando una rama principal, main, que contiene únicamente la información general del proyecto, y varias ramas secundarias donde cada miembro del grupo ha trabajado en sus propios archivos o proyectos. De esta forma evitamos conflictos y mantenemos el repositorio ordenado. Una vez que los trabajos están terminados, se pueden integrar en la rama principal.

En resumen, Git nos ha permitido trabajar de forma organizada, controlar los cambios y colaborar en grupo sin sobrescribir el trabajo de los demás.
