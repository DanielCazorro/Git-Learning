# Git-Learning
Training Skills Git/GitHub - Exercise 1


# Ejercicio 1


## ¿Qué comando utilizaste en el paso 11? ¿Por qué? 

Utilicé el comando:
`git reset --hard HEAD~1`

Este comando mueve el puntero HEAD al commit anterior y restablece el working copy al mismo estado.


## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Primero, utilicé el comando:
`git reflog`

Para localizar el ID del commit deseado.

Luego usé el comando:
`git reset —hard ff0f5d8`

Este comando mueve el puntero HEAD al commit deseado y restaura el Working Copy al estado de ese commit.


## El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?

No hubo conflictos porque la rama styled ya contenía todos los cambios de la rama main, por lo que el merge fue directo.


## El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?

Sí, ocurrieron conflictos porque el mismo archivo en ambas ramas tenía cambios diferentes en las mismas líneas.


## El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?

No hubo conflictos porque las ramas estaban en el mismo punto, por lo que fue un merge directo.


## ¿Qué comando o comandos utilizaste en el paso 25?

`git log —graph`
Este comando muestra el registro de commits en forma gráfica.


## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Sí, podría ser fast-forward ya que los cambios en las ramas eran lineales y no se modificó nada más que agregar un título.


## ¿Qué comando o comandos utilizaste en el paso 27? 

`git reset HEAD~1`
Este comando retrocede al commit anterior sin modificar el working copy.

## ¿Qué comando o comandos utilizaste en el paso 28?

`git restore git-nuestro.md`
Este comando descarta los cambios en el archivo git-nuestro.md.


## ¿Qué comando o comandos utilizaste en el paso 29?

`git branch -D title`
Este comando elimina forzadamente la rama title.


## ¿Qué comando o comandos utilizaste en el paso 30?

`git reflog`
` git reset --hard b492969`
Estos comandos te permiten volver al estado después del merge y restaurar los cambios.


## ¿Qué comando o comandos usaste en el paso 32?

`git reflog`
`git reset --hard 1ce4a2f`
Estos comandos te llevan al commit inicial del proyecto.


## ¿Qué comando o comandos usaste en el punto 33?

`git reflog`
`git reset --hard 892c7f9`
Estos comandos te llevan al estado final del proyecto con el título añadido.