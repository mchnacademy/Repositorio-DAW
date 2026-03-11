# Prácticas de Entornos de Desarrollo y Lenguaje de Marcas 1ºDWA.

## ¿Que es un Git?

- Git es un sistema de control de versiones distribuido, gratuito y de código abierto, diseñado para rastrear cambios en el código fuente durante el desarrollo de software, asu vez, este permite crear repositorios de código donde se almacena todo el historial de modificaciones de tus archivos. Al realizar cambios en el código, se crea un "commit" que registra exactamente qué se modificó, cuando se modificó y quién lo modificó.**

- En este repositorio se albergaran todas las **prácticas, ejercicios y proyectos** realizados durante el curso de **Entornos de Desarrollo** y **Lenguaje de Marcas y SGI**, con el objetivo de aprender y emplear herramientas de programación, control de versiones y desarrollo web básico.


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
  - Una vez dentro de la rama indicada emplearemos el comando **"git add (nombre_archivo)"** para añadir un archivo/trabajo/proyecto especifico al repositorio, aunque tambien se puede emplear el comando **"git add ."** para añadir todos los archivos directamente, <span style="color:red">pero ojo</span>, para que este comando funcione es necesario que todos los archivos que queramos meter se encuentren dentro de la carpeta donde se inicio el git (al ejecutar el Git Bash).
  - En caso de equivocarnos y querer deshacer un add podemos utilizar el comando **"git reset (nombre_archivo)"** para un solo archivo en especifico o **"git reset"** para todos los archivos.
  - Para confirmar los cambios se utiliza el comando **"git commit -m ("Aquí explicas qué trabajos/cambios añadiste")"** y despues **"git push -u origin (nombre-rama)"** para subir la rama al repositorio remoto (solo si es la primera vez) o **"git push"** si ya se habia añadido antes la rama al repositorio remoto.


- **Utilizacion de comandos para la implementación, eliminación y configuración de archivos en el Git:**

**(En Construccion...)**


  






















