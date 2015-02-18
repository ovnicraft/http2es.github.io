---
layout: front
title: HTTP/2
---
	
_Ver también [HTTP/2 JP](https://github.com/http2jp), mantenido por la comunidad Japonesa HTTP/2._

_Ver también [HTTP/2 ES](https://github.com/http2es), mantenido por la comunidad Japonesa HTTP/2._

## Qué es HTTP/2?

HTTP/2 es un reemplazo para como HTTP es expresado "en el público." **No**
es una re escritura del protocolo; métodos HTTP, códigos de estado y
semántica son lo mismo, y debe ser posible usar la misma API como
HTTP/1.x (posiblemente con pequeños extras) para representar el protocolo.

El enfoque del protocolo es en rendimiento; específicamente, percepción de usuario final
latencia, uso de recursos de red y servidor. El mayor objetivo es permitir el uso
de una sola conexión desde el navegador a un sitio web.

La base de este trabajo fue
[SPDY](http://tools.ietf.org/html/draft-mbelshe-httpbis-spdy-00), pero HTTP/2
ha evolucionado para tomar el apoyo de la comunidad en cuenta, incorporando varias
mejoras en el proceso.

Ver [our charter](http://datatracker.ietf.org/wg/httpbis/charter/) para más
detalles del alcance del trabajo, tanto como nuestro [Preguntas Frecuentes](/faq/).

## Estado

HTTP/2 está casi listo para ser un estándar; ha sido aprobado por el
[IESG](http://www.ietf.org/iesg/), y pronto entraría a la cola de
publicaciones del [Editor RFC](https://www.rfc-editor.org/).


## Especificaciones

HTTP/2 está compuesto de dos especificaciones:

* Protocolo de Transferencia de Hipertexto versión 2 - [borrador actual IETF](http://tools.ietf.org/html/draft-ietf-httpbis-http2/), [copia del editor](http://http2.github.com/http2-spec/)
* HPACK - Compresión de Cabecera para HTTP/2 - [borrador actual IETF](http://tools.ietf.org/html/draft-ietf-httpbis-header-compression/), [copia del editor](http://http2.github.com/http2-spec/compression.html)
 
 
## Implementaciones

Seguimos [implementaciones
conocidas](https://github.com/http2/http2-spec/wiki/Implementations) de
HTTP/2 en nuestra wiki. 
