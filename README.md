# Git-Learning
Training Skills Git/GitHub - Exercise 1

# Ejercicio 1


## ¿Qué comando utilizaste en el paso 11? ¿Por qué? 

Utilicé el comando:
`git reset --hard HEAD~1`

Lo utilicé ya que cambia el puntero HEAD a la posición precia al commit y además devuelve el working copy al mismo.



## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Primero, utilicé el comando:
`git reflog`

Con este comando localizo el id del commit buscado.

Luego usé el comando:
`git reset —hard ff0f5d8`

Con este comando (el código es el que había buscado previamente) mueve de nuevo la posición del puntero HEAD y restaura el Working Copy al commit que le hemos descrito.



## El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?

No causó ningún conflicto ya que el branch *styled* ya contenía a la rama *main*. Por ello, el realizar el *merge* no hubo problemas ya que ambos archivos eran iguales y el contenido de todas sus líneas era el mismo.



## El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?

En este caso si ha causado conflicto, porque el mismo fichero de ambas ramas tiene diferente contenido en las mismas líneas de cada fichero.


## El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?

En este caso no hubo conflicto, puesto que el puntero de la rama *main* y el de la rama *styled* estaban en el mismo lugar


## ¿Qué comando o comandos utilizaste en el paso 25?
`git log —graph`


## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Si, puesto que master y title están en la misma linea, por lo que realmente no hemos modificado nada a parte de añadir un título, y por ello no habría conflictos entre los archivos.


## ¿Qué comando o comandos utilizaste en el paso 27? 

`git reset HEAD~1`

## ¿Qué comando o comandos utilizaste en el paso 28?

`git restore git-nuestro.md`


## ¿Qué comando o comandos utilizaste en el paso 29?

`git branch -D title`


## ¿Qué comando o comandos utilizaste en el paso 30?
`git reflog`

` git reset --hard b492969`


## ¿Qué comando o comandos usaste en el paso 32?

`git reflog`

`git reset --hard 1ce4a2f`


## ¿Qué comando o comandos usaste en el punto 33?

`git reflog`

`git reset --hard 892c7f9`