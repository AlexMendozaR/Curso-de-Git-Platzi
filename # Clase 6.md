#  Clase 6

### Llaves públicas y privadas 

Para evitar que las personas puedan entender el mensaje "secreto" se debe de cifrar y así con una contraseña una persona puede ingresar. 

Pero esto tiene un problema. 
Al envíar la contraseña un hacker podría interceptar el mensaje y tomar la __"llave privada"__ 

Pero para esto se crea una llave __"Llave pública"__ la cual sólo se abre con tu __"llave privada"__ entonces tu envías esta llave pública para que funcione cómo un buzón que almacena mensaje encriptados. 

La persona receptora toma la __"llave pública"__ escribe su mensaje y lo crifra con operaciones matemáticas. Este mensaje queda crifrado en la llave pública y es sólo visible con tu __"llave privada"__ así sí un hacker quiere saber el contenido del mensaje no puede porque la llave privada está fuera de la red. 