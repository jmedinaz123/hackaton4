 • ¿Para qué sirve CSS?

El código CSS hace la vida más fácil al desarrollador front-end al separar las estructura de un documento HTML de su presentación. Dicho de otro modo el HTML actuaría como es esqueleto de la web, definiendo su estructura básica, y el CSS añadiría toda la capa de personalización sobre el que la web define su aspecto final.

Siguiendo este fundamento resulta muy fácil para un diseñador web realizar cambios en la apariencia de una web sin afectar de manera dramática a su contenido. El contenido siempre será el mismo, solo cambia como aquello que podemos ver. CSS es fácil de entender y aprender, y nos da un potente control de cómo diseñar los documentos HTML.



 • ¿Cuáles son los contras de no usar CSS? 
En caso de no usar CSS no tendremos ningun formato en nuestro sitio web

-Mayor esfuerzo. El CSS reset es un arma de doble filo: sólo nos ahorra tiempo en el caso en que no nos interese conservar los estilos por defecto. Sin embargo, hay estilos que sí puede interesarnos mantener, como por ejemplo las listas de elementos (con viñetas, indentación y otras características útiles «de fábrica»). De ser así, perderemos tiempo restaurando estilos en nuestra hoja.

-Código «sucio». Si se da el caso mencionado en el primer punto, la redefinición de estilos genera código CSS excesivo y difícil de comprender.

--Problemas de usabilidad. Algunos estilos a los que habitualmente no prestamos atención deben conservarse. Por ejemplo, quienes navegan con teclado y sin mouse, usando la tecla Tab para desplazarse, necesitan la propiedad CSS que remarca el enlace sobre el que están situados. La mayoría de los desarrolladores olvida redefinir esos estilos.

Más peso. Agregar una hoja de estilos de reset agrega peso a la página, aumentando ligeramente su tiempo de carga.



 • ¿Cuáles son los beneficios? 
Los beneficios son muchos, ya que es fundamental su uso para poder desarrollar una pagina o sistema web, nos permite personalizar cualquier detalle de diseño.

-Elimina las diferencias entre navegadores. Con un reseteo preciso y abarcador se elimina la mayoría de las diferencias de interpretación entre los browsers, ya que tamaños, márgenes, grosores, bordes y otros formatos son igualados a un estilo único y homogéneo. Ver: cross-browser testing.

-Mayor libertad. El reseteo nos brinda una hoja en blanco sobre la que podemos construir nuestros propios estilos sin tener que luchar contra los estilos del browser, que muchas veces son difíciles de identificar (y, por lo tanto, de modificar).

-Desarrollo más lógico. Una vez agregada la hoja de reset, el proceso final consistirá en agregar nuevos estilos en lugar de sobrescribirlos.