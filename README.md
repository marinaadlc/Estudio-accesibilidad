# Informe de accesibilidad
## Introducción
Este documento señala los errores de accesibilidad de la página http://getbem.com/

## Herramienta utilizada
La herramienta utilizada para analizarla es "Wave Evaluation Tool".

## Errores
En esta página encontramos los siguientes errores:

 - Errores por bajo contraste *(Contrast Errors)*
     - Solución: Cambiar el color del fondo o el texto para aumentar el contraste
     - Ocurrencia: 5 
 -  Falta de texto alternativo en una imagen(*Linked image missing alternative text*)
     - Solución: Añadir un texto descriptivo a las imágenes
     - Ocurrencia: 15
## Alertas
En esta página también encontramos las siguientes alertas:
 - Alerta por falta de región de página (* Errores*)
     - Solución: Seccionar la página usando elementos html contenedores, como "section"
     - Ocurrencia: 1 única vez, al ser relativo a la página completa.
 -  Alerta por falta de Header 1 (*Missing first level heading*)
     - Solución: Utilizar el h1 para contener el título principal de la página.
     - Ocurrencia: 1 única vez
 - Alerta por link redundante (*Redundant link*)
     - Solución: Cuando tengamos dos elementos adyacentes no deben tener un link al mismo sitio ya que el lector lo leerá dos veces. Podemos solucionarlo metiéndolos en un contenedor y añadiendo el enlace a este elemento, haciendo que cuando hagamos link dentro de la zona del contenedor, que incluirá a los dos elementos, nos lleve al enlace.
     - Ocurrencia: 3
## Trampas
Consideramos trampas a aquellos fallos que no detecta nuestra herramienta pero que no son correctos. Encontramos los siguientes:
 - Error de texto alternativo: En el hero section de la página, el texto alternativo que nos aparece para el logo es "b_", que no nos da ninguna información sobre esa imagen.
 - El icono de gitHub está insertado como iFrame, por lo que podría ser interesante añadir un título que describa que ese elemento te llevará al repositorio de gitHub de la página.
