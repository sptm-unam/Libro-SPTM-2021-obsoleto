**ARCHIVADO**

Este repositorio fue una propuesta de flujo de trabajo para la escritura colectiva del libro 
[Algoritmos Arruinados: Perspectivas situadas de tecnología musical](https://www.repositorio.fam.unam.mx/handle/123456789/139).

El pleno del SPTM decidió mudar el flujo de trabajo a [CryptPad]() por las siguientes razones:

* Utilizar un formato más familiar para la mayoría de integrantes, reduciendo la curva de aprendizaje.
* Conocer una plataforma alternativa a google docs para la creación de documentos colaborativos.

Este repositorio queda archivado de manera definitiva para servir de referencia histórica.

# Propuesta

Repositorio para trabajar en el libro del Seminario Permanente de Tecnología Musical.

## Tutorial de Git y GitHub

En Windows y Mac es recomendable bajar el [GitHub Desktop](https://desktop.github.com/) para facilitar el manejo del repositorio a través de git vinculándolo con ATOM (o con el editor de texto de su preferencia).

Para Windows se puede seguir este [tutorial](https://youtu.be/J_Clau1bYco) para usar git localmente mediante linea de comandos (*bash*) y comunicarlo con GitHub sin usar el GitHub Desktop o [este otro](https://youtu.be/ukJEPyKubzA) usando el Github Desktop.
En estos tutoriales no se explora el uso de ATOM (que ya tiene integración con git y GitHub) ni el proceso de *fork* (crear un *branch* en un repositorio) ni *pull-request* (para fucionar o hacer *merge* a la rama principal o *master*).

A continuación un pequeño tutorial para dar los primeros pasos en git y GitHub. No se presupone el uso de la aplicación de escritorio, pero sí de ATOM, y debe funcionar para todos los sistemas tipo UNIX (MacOS y Linux).


1. Crear cuenta en GitHub y solicitar acceso al repositorio en el grupo de Telegram.
2. [Instalar ATOM](https://flight-manual.atom.io/getting-started/sections/installing-atom/).
3. Descargar (en .zip y descomprimir) o clonar el repositorio (usando git).
* Descargar:
  * Ir a la página del [repositorio](https://github.com/ninioArtillero/Libro---Seminario-Perm.-de-Tec.-Musical).
  * Picar el ícono verde y elegir "Download ZIP".
* Clonar:
    * Abrir terminal e ir a la carpeta donde se quiere guardar el repo, por ejemplo: `cd /home/usuario/documents`
    * Ejecutar `git clone https://github.com/ninioArtillero/Libro---Seminario-Perm.-de-Tec.-Musical.git`
4. En ATOM elegir la opción *Add Project Folder...* en *File* y seleccionar la carpeta del repositorio. Se abrirá la pestaña *Project*.
5. En el menu de la barra inferior, a la derecha, click *branch* o *master* y click en *New Branch*.
Nombrarla con el siguiente formato (propuesta de convención):
`nombre-del-usuario/palabra-clave`. Por ejemplo `xavier/remix`.
6. En la pestaña *Project* click-derecho en la carpeta correspondiente a su grupo temático y elegir *New Folder* y ponerle su nombre.
Por ejemplo `xavier`.
Click-derecho a la carpeta creada y elegir *New File* y llamarlo `README.md`.
7. Doble click al nuevo archivo en la pestaña *Project* lo abrirá en una pestaña para añadir texto.
Aquí escriban un abstract o resumen tentativo (cualquier longitud, mínimo una palabra, es una prueba).
Pueden formatearlo facilmente checando la [cheatsheet de Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
Para ver como queda el texto formateado entrén al menú superior *Packages*, elegir *Markdown Preview* y seleccionen *Toggle Preview*.

8. Una vez terminado el texto salvenlo (`ctrl/cmd + s` mientras el cursor está en el texto del documento).

9. Ir al menú superior *View* y seleccionar *Toggle Git Tab*. Aparecera una pestaña donde se habrán registrado los cambios realizados. Seleccionen *Stage All* junto a *Unstaged Changes*.

10. Agreguen un mensaje que diga "Primer commit y abstract de mi artículo" y click a `Commit to nombre-del-usuario/palabra-clave`.

11. Click al pequeño botón *Publish* que está a la derecha en la barra inferior.

12. Una vez terminado el proceso de subida podrán ver el archivo que han creado yendo al [repositorio](https://github.com/ninioArtillero/Libro---Seminario-Perm.-de-Tec.-Musical) y eligiendo el nombre de su *branch* en el menú desplegable que dice *master*

Cada *branch* es un registro "histórico" que permite dar seguimiendo al desarrollo de un proyecto, documentando sus cambios. El *master* es un *branch* como cualquier otro, que por convención se usa como "centro". Mientras trabajen en un *branch* pueden hacer todas las modificaciones que quieran a cualquier documento del repo. Luego en GitHub se puede realizar un **PULL-REQUEST**, el cual permite revisar los cambios efectuados (comparando linea a linea) para posteriormente hacer un **MERGE**, esto es integrar los contenidos.

## Siguientes pasos

Añadir a su carpeta un documento *Artículo.txt* de texto plano donde se empiece a componer su artículo. Al terminar su **sesión de trabajo**, después de salvar, seguir los pasos 9 y 10 (poniendo un comentario al *commit* que describa sintéticamente los cambios realizados o añadiduras durante esa sesión de trabajo) hará que los cambios queden guardados en git localmente. Para "subir" estos cambios al repositorio en Github hay hacer click en el botón *Push* o, si no está, click-derecho *Fetch* de la barra inferior y click en *Push*.

Es **importante** notar que los cambios serán enviados al *branch* en el que estén trabajado (indicado por su nombre en el menu que está abajo a la derecha en ATOM). Si cambian de *branch* posiblemente verán cambiar los contenidos de la carpeta del proyecto y/o el texto de los documentos (dependerá de las diferencias locales entre una y otra *branch*).

Recuerden que esto es una **propuesta**. Aunque decidamos cambiar de herramienta y/o plataforma este tutorial y revisar las **referencias** de abajo puede permitirnos una desición más informada (y de perdida una introducción a esta herramienta ideosincrática del desarrollo de software).

## Estructuración del flujo de trabajado

Haciendo click en *Issues* debajo del título del repo verán algunos temas por resolver. De momento: características de este tutorial y el diseño del flujo de trabajo, es decir: la manera en que vamos a administrar el repo y coordinar el trabajo (cuyas últimas resoluciones se irán publicando en este mismo documento).

## Referencias

[GitHub Flow: Guía Básica](https://guides.github.com/introduction/flow/)

[Usar Git para escritura](https://opensource.com/article/19/4/write-git)

[Colaboración con Git](https://medium.com/anne-kerrs-blog/using-git-and-github-for-team-collaboration-e761e7c00281)

[Cheatsheet de Markdown (para dar formato a archivos con extensión .md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Manual "Pro Git"](https://git-scm.com/book/en/v2)

[Borrar *branches* locales y remotos (limpieza)](https://railsware.com/blog/git-housekeeping-tutorial-clean-up-outdated-branches-in-local-and-remote-repositories/)
