# Clase 11 

El comando rebase une los cambios de una rama a otra, sin hacer merge. 
Agrega el historial de la rama trabajada a la nueva rama. 

Así podemos mantener la historia de commits limpia. 

__OJO:__ Este rebase sólo debe ser usado en repositorio locales y no envíado a repositorios externos, porque se pierde el log y crea conflicto con las versiones de otros desarrolladores. 

El comando __rebase__ es totalmente silencioso, sí borras la rama no queda registro de su existencia pero si los commit en la rama que envíaste la información. 