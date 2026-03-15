# Prácticas de Entornos de Desarrollo y Lenguaje de Marcas 1ºDWA.

## ¿Que es un Git?

- Git es un sistema de control de versiones distribuido, gratuito y de código abierto, diseñado para rastrear cambios en el código fuente durante el desarrollo de software, asu vez, este permite crear repositorios de código donde se almacena todo el historial de modificaciones de tus archivos. Al realizar cambios en el código, se crea un "commit" que registra exactamente qué se modificó, cuando se modificó y quién lo modificó.

- En este repositorio se albergaran todas las **prácticas, ejercicios y proyectos** realizados durante el curso de **Entornos de Desarrollo** y **Lenguaje de Marcas y SGI**, con el objetivo de aprender y emplear herramientas de programación, control de versiones y desarrollo web básico.

---

## Contenido del repositorio:

- **Entornos de Desarrollo**
  - Configuración de IDEs y editores de código.
  - Uso de Git, GitHub y derivados.
  - Gestión de proyectos y control de versiones.
  - Automatización de tareas.
  - Analisis de metodologias de desarrollo software.

- **Lenguaje de Marcas**
  - HTML: estructura básica de páginas web.
  - CSS: estilos y diseño visual.
  - Proyectos de práctica integrando HTML y CSS.
  - Actividades de XML/DTD.
  - Actividades de SXD.

- **Archivos Adicionales**
  - Documentos PDF y presentaciones de prácticas.
  - Recursos de apoyo utilizados durante las prácticas.

---

## Instrucciones de uso y tips:

- **Primros pasos: Creacion de un Git.**

  - Lo primero que necesitaremos será tener una cuenta de GitHub, en la cual se  mostrara el git que crearemos, e instalar **Git GUI y Git Bash**, donde introduciremos los comandos necesarios para empezar a crear nuestro Git.
  - Una vez creada la cuenta de GitHub y descargado Git Bash y Git GUI, nos dirigiremos a la esquina superior izquierda y le daremos a un boton de color rojo, el cual nos permitira crear nuestro repositorio.
  - Cuando ya tengamos creado el repositorio se nos permitira añadir nuestros trabajos a él, y trabajar con Git Bash.
  - Para poder trabajar con el repositorio e incorporar nuestros proyectos necesitaremos clonarlo (para Git Bash), para ello emplearemos el comando **"git clone https://github.com/mchnacademy/Repositorio-DAW.git"**.
  - Tambien se puede crear un repositorio desde Git Bash, utilizando el comando **"git init"**, lo que creara una carpeta .git donde almacenaremos los proyectos que albergará nuestro repositorio.

- **Implementacion de proyectos en el Git:**

  - Al entrar por primera vez en Git Bash se nos situara en la rama main (principal) del repositorio, allí solo dejaremos el archivo README.md, si queremos añadir archivos sera mejor hacerlo en una rama diferente (branches), para poder crearla usaremos el comando **"git branch (nombre_rama)"**, y **"git checkout (nombre_rama)"** para posicionarnos en ella para añadir los trabajos directamente.
  - Tambien se podria emplear el comando **"git checkout -b (nombre_rama)"**, que creara la rama y nos posicionara directamente en ella.
  - Para verificar que estamos en la rama correcta usaremos el comando **"git branch"**, este nos dira en que rama nos encontramos.
  - Una vez dentro de la rama indicada emplearemos el comando **"git add (nombre_archivo)"** para añadir un archivo/trabajo/proyecto especifico al repositorio, aunque tambien se puede emplear el comando **"git add ."** para añadir todos los archivos directamente, pero ojo, para que este comando funcione es necesario que todos los archivos que queramos meter se encuentren dentro de la carpeta donde se inicio el git (al ejecutar el Git Bash).
  - En caso de equivocarnos y querer deshacer un add podemos utilizar el comando **"git reset (nombre_archivo)"** para un solo archivo en especifico o **"git reset"** para todos los archivos.
  - Para confirmar los cambios se utiliza el comando **"git commit -m ("Aquí explicas qué trabajos/cambios añadiste")"** y despues **"git push -u origin (nombre-rama)"** para subir la rama al repositorio remoto (solo si es la primera vez) o **"git push"** si ya se habia añadido antes la rama al repositorio remoto.
 
---

## Uso de comandos claves para la elaboreacion del repositorio:
 
- **Utilizacion de Commit:**

  - Un commit es como un “fotograma” de tu proyecto, se encarga de guardar los cambios que hiciste en tu código en un momento determinado.Cada commit tiene un mensaje que explica que cambios se han hecho y un id unico que permite volver a ese estado previo.

  - Una vez ejecutado el comando **"git add ."** para agregar trabajos a un repositorio, debemos emplear el comando **"git commit -m (Mensaje que explique los cambios)"** para confirmar los cambios.
 
  - Despues podemos usar los comando **"git status"** y **"git log"** para mostrar el estado de los archivos y todos los commits que se han realizado.
 
  - Por ultimo, para subir nuestros commits a GitHub al repositorio remoto (el original) usaremos el comando **"git push origin main"** o **"git push origin (nombre_rama)"** para agrgar los cambios al main o a otra rama.
 
  - Este ultimo paso se hace debido a que al trabajar en Git Bash, todos los cambios y ajustes que hagamos no se implementaran instantaneamente en el repositorio remoto (el de GitHub), ya que nosotros estamos trabajando en una version clonada del original, hecha para organizar y optimizar el funcionamiento del repositorio. Por ello, debemos emplear varios comando, para que si se registre en el repositorio remoto.

- **Utilizacion de Pull request:**

  - Un Pull Request es una solicitud que se hace para proponer que los cambios realizados en una rama se integren en otra rama, normalmente en la rama principal (main), lo que facilita revisar el codigo y mantener organizado el trabajo.

  - Primero se crea una rama para trabajar usando el comando **"git checkout -b (nombre_rama)"**, a continuacion añadimos los trabajos que queramos y los guardamos con los siguientes comandos **"git add . y 
git commit -m "Descripción de los cambios""**, y por ultimo añadimos la rama creada a GitHub con **"git push -u origin nombre_rama"**.

  - Posteriormente haremos los siguientes pasos:

    - Ir al repositorio en GitHub, una vez lo tengamos creado.

    - Allí aparecerá un botón que dice Compare & Pull Request.

    - Hacemos clic en el boton.

    - Escribimos una descripcion de los cambios.

    - Y pulsamos Create Pull Request.

  - Ahora otros usuarios pueden revisar el código antes de aceptarlo, mpara asegurarse de que no hay ningun error crítico.

- **Utilizacion de Merge:**

  - Un Merge es la acción de unir o fusionar los cambios de una rama con otra dentro de un repositorio de Git, sirve para implementar cambios en una rama en especifico o en la misma main.
 
  - Para realizarlo haremos los siguientes pasos:
 
    - Revisar los cambios.

    - Pulsar Merge Pull Request.

    - Confirmar con Confirm Merge.
   
  - Esto unirá las dos ramas implicadas.
 
  
  


  






















