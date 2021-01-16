# Propuesta:

Repositorio para trabajar en el libro del Seminario Permanente de Tecnología Musical.


A continuación un pequeño tutorial para que probemos como será colaborar usando git y GitHub.

En Windows y Mac es recomendable bajar el [GitHub Desktop](https://desktop.github.com/) para facilitar el manejo del repositorio a través de git vinculándolo con ATOM. Los siguientes pasos no presuponen el uso de la aplicación de escritorio y deben funcionar para todos los sistema tipo UNIX (MacOS y Linux).

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
6. En la pestaña *Project* click-derecho en la carpeta del repo y elegir *New Folder* y ponerle su nombre.
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

Un siguiente paso sería añadir a su carpeta un documento *Artículo.txt* de texto plano donde se empiece a componer su artículo. Al terminar su sesión de trabajo, después de salvar, seguir los pasos 9 y 10 (poniendo un comentario al *commit* que describa sinteticamente los cambios realizados o añadiduras) hará que los cambios queden guardados en git localmente. Para "subir" estos cambios al repositorio en Github hay hacer click en el botón *Push* o, si no está, click-derecho *Fetch* de la barra inferior y click en *Push*.

Lo que faltará discutir será explicar como usaremos el "pull request" para integrar el trabajo realizado en los *branches*. Cabe decir que es importante, mientrás afinamos el uso de esta herramienta y nos organizamos, sólo editar los documentos de sus carpetas.

## Referencias

[Usar Git para escritura](https://opensource.com/article/19/4/write-git)

[Colaboración con Git](https://medium.com/anne-kerrs-blog/using-git-and-github-for-team-collaboration-e761e7c00281)

[Cheatsheet de Markdown (para dar formato a archivos con extensión .md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
