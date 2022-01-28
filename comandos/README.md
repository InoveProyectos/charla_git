# Como cambiar el author de un comit
- Supongamos que tenemos esta historia de commits --> A-B-C-D-E-F con F como HEAD (el último commit realizado)
- En este caso deseamos modificar el author del commit C y D. El anterior commit a estos es el commit "B".

1- Realizar un "git log" y copiar el hash del commit B.\
2- Iniciar un git rebase (hasta que no se termine este proceso su repositorio quedará inutilizable). ejecutar "git rebase -i <hash_commit_B>".\
3- Se abrirá una pantalla en su editor por defecto. En los commits que desea modificar cambiar la palabra "pick" por "edit" y cerrar el editor salvando el archivo.\
4- El sistema se posicionará primero en el commit C, ejecutar el comando para cambiar de nombre: git commit --amend --author="Author Name <email@address.com>"\
5- Luego debemos pasar al commit siguiente, ejecutando "git rebase --continue".\
6- El sistema se posicionará primero en el commit D, ejecutar el comando para cambiar de nombre: git commit --amend --author="Author Name <email@address.com>"\
7- Ejecutar "git rebase --continue" para pasar al siguiente.\
8- Cuando hayamos completado la edición de todos los commits, el sistema finalizará con "Successfully rebased and updated "\
9- Pushear lo cambios con "git push -f" para actualizar el repositorio remoto.

Referencia:
https://stackoverflow.com/questions/3042437/how-to-change-the-commit-author-for-one-specific-commit
