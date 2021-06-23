 
Paso 11

Git reset —hard HEAD~1 

Ya que este es el paso para volver al primer commit donde se realizo este cambio y ya que debía dejar como esta estaba le metí el comando hard.

 Paso 12

Git reflog

Git reset —hard ab11d61

Use estos pasos ya que como se habia borrado los datos anteriores del archivo y se desactivo el comió la unica forma de acceder era por medio de buscar en reflog los ultimos pasos y el indentificador del commit desactivado. Hay en encontré el hash y le hize otro reset hard para volver todo a su posicion original


 El merge del paso 13 no causo nigun conflicto

El merge del paso 19 si causo un conflicto debido a que algunas lineas eran iguales y git no estaba seguro de estuviera correcto por eso te manda un error de conflicto

En el paso 21 No causo ningún conflicto

En el paso 25 puse el comando git log —graph

Paso 26

Si es posible hacer un fast forward ya que lo único que cambia en este caso es que se absorbe lo que no crearía otro comit extra y las dos ramas estaría en el mismo comit

Paso 27
Deshago el merge con un git reset —hard 9c652accfd22f5f0ffb7ca23ac710bac905adef9

28 no he podido descartar los cambios ya que hize un Git reset —hard y no pude hacer hacer un restore

Paso 29 
git branch -d title

Paso 30 
git reset --hard aebb032

Paso 31
 git reset 95110a17a47696412af4ab21db583c3f59ac5

Paso 32
git reset 95110a17a47696412af4ab21db583c3f59ac5

Paso 33
Git reset 
9c652ac
