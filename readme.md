Paso 11: git reset --hard HEAD~1
Porque deshace el último commit y lo que había en el working copy de manera que todo quede como antes.

Paso 12: git reflog para obtener el hash de la modificacion.
git reset con el hash para volver a establecer ese cambio
git add y git commit para incluirlo en el repositorio

Paso 13: No causó ningún conflicto, porque no había cambios en master que no estuvieran reflejados en styled.

Paso 19: No hubo conflictos. Creo que debería haber habido un conflicto, pero en el archivo original había saltos de línea, y en el de htmlify, y por eso creo que no dio conflictos (reemplazó líneas en blanco con líneas con texto).

Paso 21: No hubo conflictos, porque master no tenía modificaciones.

paso 25: git graph

paso 27: git reset

paso 28: git restore

paso 29: git branch -d title

paso 30: git reflog para encontrar el hash, git reset hash

paso 32: git reset hash

paso 33: git reset hash
