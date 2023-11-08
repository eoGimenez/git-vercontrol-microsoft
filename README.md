** Empezando el challenge de microsoft

- git log --oneline

- git diff << muestra las diferencias entre el ultimo commit y el archivo actualmente

- git commit -am << shotcut de git commit -a -m

- git add -A << agrega los nuevos archivos que no estan siendo trackeados

- git add . << agrega como el -A pero tambien guarda cambios (el de siempre)

- git commit --amend --no-edit << es para agregar alguna pequeña modificacion un codigo sin querer crear una nueva referencia incluso sin cambiar el titulo del commit

- git checkout -- nombreDelArchivo << Recupera la ultima version guardad por git de un archivo eliminado

- Si usamod "git rm nombreDelArchivo" eliminara el archivo del track de git y no podremos usar el "git checkout -- nombreDelArchivo"

- git reset HEAD nombreDelArchivo << Recupera la ultima version del archivo que fue eliminado del track de git

- git reset --hard HEAD^ << hace el HEAD el commit anterior al que estas.

- git revert --no-edit HEAD << Hace un revert del ultimo commit, creando un nuevo track, agregando Revert "nombre del ultimo commit"

- git checkout trackId . << Esto recupera la version anterior que querramos, importante el " . " al final para claramente indicar que es todo