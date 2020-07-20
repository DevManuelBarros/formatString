FormatString
------------

Pequeña función para darle colores a las aplicaciones sin demasiadas vueltas y 
sin demasiadas opciónes.


```
formatString(
		text  : (obligatorio) . El texto a formatear.
		color : (obligatorio) . El color del texto.
		b     : (opcional). Por defecto sin fondo.
		t     : (opcional). Default. El estilo que queremos que tenga, hay 7 opciones, incluye negrita, italic, etc.
	     )
```


Descargar con wget, y luego importar... 

wget 'https://github.com/DevManuelBarros/formatString'

from formatString import formatString
 
print(formatString('text', 'verde'))


Dudas consulta insultos a: dev.manuel.barros@gmail.com
