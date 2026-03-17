# ✨Prácticas de Entornos de Desarrollo y Lenguaje de Marcas 1ºDWA.✨

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

- **Primeros pasos: Creacion de un Git.**

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
 
- **Utilizacion de Commits:** 💾

  - Un commit es como un “fotograma” de tu proyecto, se encarga de guardar los cambios que hiciste en tu código en un momento determinado.Cada commit tiene un mensaje que explica que cambios se han hecho y un id unico que permite volver a ese estado previo.

  - Una vez ejecutado el comando **"git add ."** para agregar trabajos a un repositorio, debemos emplear el comando **"git commit -m (Mensaje que explique los cambios)"** para confirmar los cambios.
 
  - Despues podemos usar los comando **"git status"** y **"git log"** para mostrar el estado de los archivos y todos los commits que se han realizado.
 
  - Por ultimo, para subir nuestros commits a GitHub al repositorio remoto (el original) usaremos el comando **"git push origin main"** o **"git push origin (nombre_rama)"** para agrgar los cambios al main o a otra rama.
 
  - Este ultimo paso se hace debido a que al trabajar en Git Bash, todos los cambios y ajustes que hagamos no se implementaran instantaneamente en el repositorio remoto (el de GitHub), ya que nosotros estamos trabajando en una version clonada del original, hecha para organizar y optimizar el funcionamiento del repositorio. Por ello, debemos emplear varios comando, para que si se registre en el repositorio remoto.
 
- **Creacion y utilizaccion de ramas (branches):** 🌿

  - Una rama es como una línea paralela de desarrollo en la que puedes hacer cambios sin afectar a la rama principal (main), ideal para probar cosas nuevas y para corregir errores.
 
  - Para crear una rama desde Git Bash usaremos el comando **"git branch (nombre_rama)"**, y para posicionarnos en ella usaremos **"git checkout (nombre_rama)"**, tras ello ya podremos subir nuestros proyectos a esa rama.
 
  - Para subir la rama a GitHub y que sea visible para todos usaremos el comando **"git push origin (nombre_rama)"**.
 
  - Si queremos ver las ramas existentes en nuestro repositorio podemos usar **"git branch"**, que mostrará en que rama estamos y listara las demas.
 
  - Si quisiesemos volver a la rama main (principal) usariamos **"git checkout main"**.

- **Utilizacion de Pull request:** 📬

  - Un Pull Request es una solicitud que se hace para proponer que los cambios realizados en una rama se integren en otra rama, normalmente en la rama principal (main), lo que facilita revisar el codigo y mantener organizado el trabajo.

  - Primero se crea una rama para trabajar usando el comando **"git checkout -b (nombre_rama)"**, a continuacion añadimos los trabajos que queramos y los guardamos con los siguientes comandos **"git add . y 
git commit -m "Descripción de los cambios""**, y por ultimo añadimos la rama creada a GitHub con **"git push -u origin (nombre_rama)"**.

  - Posteriormente haremos los siguientes pasos:

    - Ir al repositorio en GitHub, una vez lo tengamos creado.

    - Allí aparecerá un botón que dice Compare & Pull Request.

    - Hacemos clic en el boton.

    - Escribimos una descripcion de los cambios.

    - Y pulsamos Create Pull Request.

  - Ahora otros usuarios pueden revisar el código antes de aceptarlo, mpara asegurarse de que no hay ningun error crítico.

- **Utilizacion de Merge:** 🔀

  - Un Merge es la acción de unir o fusionar los cambios de una rama con otra dentro de un repositorio de Git, sirve para implementar cambios en una rama en especifico o en la misma main.
 
  - Para realizarlo haremos los siguientes pasos:
 
    - Revisar los cambios.

    - Pulsar Merge Pull Request.

    - Confirmar con Confirm Merge.
   
  - Esto unirá las dos ramas implicadas.
 
  - Si queremos hacerlo desde Git Bash usaremos el comando **"git checkout main"** para situarnos en el main y luego usaremos el comando **"git merge (nombre_rama)"** para fusionar los cambios.
 
- **Creacion de archivo .gitignore:** 🚫

  - Un .gitignore es un archivo que le dice a Git y a GitHub qué archivos NO deben subirse al repositorio. Esto se usa para evitar subir cosas innecesarias como configuraciones personales, archivos temporales o binarios.
 
  - Para crearlo haremos lo siguienet:

    - Ve a tu repositorio en GitHub.
   
    - Haz clic en Add file.
   
    - Selecciona Create new file.
   
    - Nombra el archivo como .gitignore.
   
    - Y dentro pones los archivos que se ignoraran.
   
    - Por ultimo le das a Commit new file.
   
- **Conflicto de fusion:** ⚠️

  - Un conflicto de fusión ocurre cuando Git no puede combinar automáticamente los cambios de dos ramas porque modificaron la misma línea en el mismo archivo.
 
  - Para provocarlo haremos lo siguiente:

    - Usaremos git checkout -b rama1.
      
    - Ahora git checkout main.
      
    - Y por ultimo git checkout -b rama2.
   
    - Ahora haremos los commits desde cada rama:

      - git add README.md (desde la rama 1).
     
      - git commit -m "Cambios desde rama1" (desde la erama 1).
     
      - git add README.md (desde la rama 2).
     
      - git commit -m "Cambios desde rama2" (desde la rama 2).

    - Ahora trataremos de fusionarlas:

      - git checkout rama1.
     
      - git merge rama2.
     
    - Y de la nada Git detectara un conflicto (cambios incompatibles en una misma linea).
   
    - Para solucionarlo solo tendremo que editar el archivo conflictivo ( en este caso el readme) y decidir que se quedara y que no, y emplear de nuevo **"git add"** y **"git commit"**.
   
    - En resumen, un conflicto son cambios incompatibles que ocurren en una misma linea cuando se modifica un archivo en dos ramas diferente y se intenta fusionarlas, y para solucionarlo hay que editar el archivo y elegir que modificacion se quedara y cual no, y confirmar los cambios.
   
- **Version final:** 🏁

  - La “versión final” de un proyecto es básicamente el estado del proyecto que consideras completo y listo para entregar o publicar.
 
  - Para crear iremos a GitHub y haremos clic en release y le daremos a crete new release, despues solo crearemos un tag con el nombre "v1.0-entrega" y rellenaremos de manera automatica el contenido.
 
  - Por ultimo aceptaremos los cambios y ya estaria disponible para visualizarlo.
 
---

## Participantes del grupo: 📖

 - Trabajo realizado por 👑Guido, 👑Chen, 👑Samuel y 👑Dennis, alumnos de 1ºDWA IES. Clara del Rey  2025/2026.



<div align="center">
  <img src=https://i.pinimg.com/originals/33/1d/6d/331d6d029a5a93396cc9a0a5a75cfe74.jpg>
  <img src=https://i.pinimg.com/originals/33/41/c1/3341c10a07672ef6b5d57cb968c7b544.jpg>
  <img src=https://i.pinimg.com/736x/4d/32/e7/4d32e7b9518224e552845fc4581631fd.jpg>
  <img src=https://static.tvtropes.org/pmwiki/pub/images/samsprattblues.png>
</div>
  
  


  






















