# Propuesta:

Repositorio para trabajar en el libro del Seminario Permanente de Tecnología Musical.

A continuación presento un pequeño tutorial para que probemos como será colaborar usando git y GitHub.

En Windows y Mac es recomendable bajar el [GitHub Desktop](https://desktop.github.com/) para facilitar el manejo del repositorio a través de git vinculándolo con ATOM.

1. Crear cuenta en GitHub.
2. [Instalar ATOM](https://flight-manual.atom.io/getting-started/sections/installing-atom/).
3. Descargar (en .zip y descomprimir) o clonar el repositorio (usando git).
* Descargar:
  * Ir a la página del [repositorio](https://github.com/ninioArtillero/Libro---Seminario-Perm.-de-Tec.-Musical).
  * Picar el ícono verde y elegir "Download ZIP".
* Clonar:
    * Abrir terminal e ir a la carpeta donde se quiere guardar el repo, por ejemplo: `cd /home/usuario/documents`
    * Ejecutar `git clone https://github.com/ninioArtillero/Libro---Seminario-Perm.-de-Tec.-Musical.git`
4. En ATOM elegir la opción *Add Project Folder...* en *File* y seleccionar la carpeta del repositorio. Se abrirá la pestaña *Project*.
5. En el menu de la barra inferior seleccionar *branch* y picar *New Branch*.
Nombrarla con el siguiente formato (propuesta de convención):
`nombre-del-usuario/palabra-clave`. Por ejemplo `xavier/remix`.
6. En la pestaña *Project* picar con botón secundario la carpeta del repo y elegir *New Folder* y ponerle su nombre.
Por ejemplo `xavier`.
Picar con botón secundario la carpeta creada y elegir *New File* y llamela *README.md*.
7. Doble click al nuevo archivo abrirá una pestaña para añadir texto.
Aquí escriban un abstract o resumen tentativo (cualquier longitud, es una prueba).
Pueden formatearlo facilmente checando la [cheatsheet de Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
Pueden ver como queda el texto entrando al menú superior *Packages*, elegir *Markdown Preview* y picar *Toggle Preview*.

8. Una vez terminado el texto salvenlo (ctrl/cmd + s).

9. Ir al menú superior *View* y picar *Toggle Git Tab*. Aparecera una pestaña donde se habrán registrado los cambios realizados. Seleccionen *Stage All* junto a *Unstaged Changes*.

10. Agreguen un mensaje que diga "Primer commit y abstract de mi artículo" y pica *Commit to `nommbre-del-usuario/palabra-clave`*.

11. Picar en *Publish* en la pestaña inferior.

## Referencias

[Usar Git para escritura](https://opensource.com/article/19/4/write-git)

[Colaboración con Git](https://medium.com/anne-kerrs-blog/using-git-and-github-for-team-collaboration-e761e7c00281)

[Cheatsheet de Markdown (para dar formato a archivos con extensión .md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Proyecto del Laboratorio de Informática Musical de la Facultad de Música UNAM.
