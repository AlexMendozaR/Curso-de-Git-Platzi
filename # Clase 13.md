# Clase 13

## Git clean

Nos ayuda a eliminar archivo que no estén siendo trackeados.
Este elimina archivo clonados.

__PERO TOMA CÓMO EXCEPCIÓN LOS ARCHIVOS DEL .GITIGNORE__

Para poder ver que archivos se van a eliminar sin eliminarlos debemos usar el comando

__git clean --dry-run__ 

Y para eliminar los archivos debemos usar el comando 

__git clean -f__ 

**-f significa FORCE, es decir, fuerza el delete** 