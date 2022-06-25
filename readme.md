# Práctica de Git

*NOTA: en lugar de MAIN tengo la rama MASTER. En discord has dicho que para este módulo lo permitías. Para el próximo lo clonaré de github y lo haré con MAIN. Gracias!*

------

## Ejercicio 1


* ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1
He hecho un reset --hard para borrar los cambios del working copy.


* ¿Qué comando o comandos utilizaste en el paso 12?

git reflog para ver los pasos que he dado y recuperar la referencia del commit anterior.
git reset --hard 0456c97 para volver a él.


* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

Me dice "Already up to date." porque el único commit de master es el primero, que es común a todas las ramas.


* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí, porque el archivo git-nuestro.md tiene diferentes versiones en cada rama.


* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, ningún conflicto.


* ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph


* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Sí, porque no hemos creado nuevos commits en Master después de crear Title, con lo que no se han "ramificado" y basta con mover la etiqueta de master al siguiente commit de Title.


* ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1


* ¿Qué comando o comandos utilizaste en el paso 28?

git reset --hard


* ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title


* ¿Qué comando o comandos utilizaste en el paso 30?

git reflog para ver la referencia
git reset --hard 9ccd3e8 para volver a ese commit


* ¿Qué comando o comandos utilizaste en el paso 32?

git reflog para ver la referencia
git checkout de0e8e8 para ir a él

* ¿Qué comando o comandos utilizaste en el paso 33?

git reflog para ver la referencia
git checkout 9ccd3e8 para ir a él

------

## Ejercicio 2

*Pull request enviado y sin conflictos con una cita de Matrix*