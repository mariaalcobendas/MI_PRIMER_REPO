# Responde por escrito, con tus palabras:

## 1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo?

La principal diferencia es que preparar un archivo sirve para indicar a Git qué cambios se quieren incluir en la siguiente confirmación, mientras que confirmar el archivo es guardar los cambios en un repositorio local.

## 2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene?

Cuando el archivo se ha modificado y no está confirmado. El riesgo que tiene es que es irreversible: no puedes recuperarlos.

## 3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?

El trabajo de una rama creada a partir de la principal sólo se verá cuando estemos situados en esa rama, es decir, si nos situamos en otra rama veremos los cambios hechos desde que se creo esa rama.

## 4. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?

Porque no hubo cambios en las nuevas líneas que se escribieron en el documento principal. Al intentar fusionar la rama-b, como en esas líneas se escribieron otras cosas, dio conflicto.

## 5. ¿Para qué sirve crear una rama de experimento, aunque luego se borre?

Para poder volver a la versión principal en caso de cometer errores, o juntar la rama si queremos agregar los cambios a la rama principal.

## 6. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo?

Se puede copiar y pegar el código del commit anterior y agregar lo de una versión más nueva.