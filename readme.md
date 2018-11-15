

      Plantilla para proyectos Open Hardware
=======================================================

Este repositorio tiene el objetivo de servir de plantilla
para facilitar la documentaci�n de proyectos Open-Hardware.

Las carpetas propuestas en esta estructura est�n basados
en las recomendaciones de buenas pr�cticas de la OSHWA
traducidas al espa�ol que se encuentran disponibles en
http://www.openhardware.sv/acerca-de/buenas-practicas-para-el-hardware-de-fuente-abierta/

Puedes modificar este documento como mejor se ajuste a tus
necesidades sobreescribiendo los textos en cada p�rrafo y
agregando la informaci�n y archivos que consideres conveniente.

Inicia borrando esta secci�n incluyendo esta l�nea.


Nombre de tu proyecto
=====================

Escribe aqu� una descripci�n breve de dos o tres p�rrafos
en donde expliques: �Qu� es tu proyecto? �Para qu� sirve? y �C�mo
hacerlo funcionar?

Procura no utilizar t�cnicismos o lenguaje complicado, recuerda
que las personas que leer�n esta descripci�n puede que no tengan
tu mismo nivel de conocimiento o tu misma �rea de experiencia.

Explica br�vemente el funcionamiento esperado de tu proyecto, no es
necesario que escribas todo en detalle, si el funcionamiento requiere
una explicaci�n m�s detallada puedes hacer referencia a un sitio web
o a otro archivo de texto dentro de la carpeta "docs".

Es muy �til que indiques el nivel de desarrollo de este proyecto sea
"estable", "beta", "incompleto" o "a-penas-funciona".

Tambi�n puedes agregar en esta secci�n los cr�ditos correspondientes
si tu proyecto se deriva de otro, nombres o pseud�nimos de las
personas que colaboraron, licencia y fecha de �ltima actualizaci�n.

�ltimas adiciones
=================

Coloca en esta secci�n los �ltimos cambios relevantes o correcciones
que hayas realizado a tu proyecto. Es importante que notifiques sobre
cambios que modifiquen el comportamiento de tu proyecto o las salidas
que este genera.

Ejemplo de cambios en la �ltima versi�n 0.1alpha:

* Agregados textos de ejemplo
* Agregado n�meros de versi�n

Correcciones:

* Corregidos errores de ortograf�a

No es necesario que coloques todo el historial de cambios, en vez de eso
puedes crear un archivo en esta carpeta llamado "changelog.txt" con el hist�rico
completo (preferiblemente en orden cronol�gico inverso):

> Puede revisar el historial de cambios completo en el archivo changelog.txt

Costo/Lista de Materiales
=========================

Si la lista de materiales de este proyecto es corta puedes inclu�rla aqu�, en
caso contrario puedes crear un archivo llamado "bom.csv" o un archivo de hoja de
c�lculo donde puedes detallar la lista de materiales y costos. Procura utilizar
formatos abiertos en la medida de lo posible, por ejemplo eligiendo ODS sobre
Excel.

Pre-requisitos/Requerimientos
=============================

Dedica esta secci�n a explicar en detalle �Qu� se requiere para hacer funcionar
tu proyecto?. Debes colocar los requerimientos o pre-requisitos del software
para hacerlo funcionar y herramientas para construirlo.

Para el hardware puedes especificar herramientas o maquinaria espec�fica que se
necesite para construir el proyecto.

Ejemplo:

Requerimientos de software:

* IDE Arduino.

Herramientas requeridas:

* Pinza cortadora de cable.


Construcci�n y uso
==================

Si el procedimiento de construcci�n es sencillo, puedes detallarlo en esta
secci�n, en caso contrario puedes crear un archivo "build.txt" donde detalles el
procedimiento a seguir.

De igual manera si el procedimiento de utilizaci�n del software asociado a tu
proyecto es sencillo puedes explicarlo aqu�. En caso de que las instrucciones
sean muy extensas, puedes crear un archivo "usage.txt" y hacer referencia
al mismo en esta secci�n.

Carpetas
========
La estructura de carpetas es muy importante en un proyecto, te permitir� tener
tus proyectos organizados y permitir� a otros compartir f�cilmente cambios o 
mejoras. Esta estructura no est� escrita en piedra y puedes modificarla seg�n
se adopte mejor a tus necesidades.

Recuerda que dentro de cada carpeta es muy recomendable que incluyas un archivo
llamado "readme.txt" donde detalles los contenidos de la misma.

En la estruuctura de directorios se recomienda incluir por al menos las
siguientes carpetas:

* *doc*: Utiliza esta carpeta para ingresar toda la documentaci�n que consideres
necesaria para tu proyecto. De preferencia utiliza formatos libres como "ODF"
o simples archivos de texto, si puedes crear una p�gina web en HTML recuerda
renombrar el archivo principal como "index.html" para que pueda ser accedido
f�cilmente en caso de que alguien copie esta carpeta en un servidor web.
* *src*: Coloca en esta carpeta todos los archivos de c�digo fuente del software
de control de tu proyecto Open Hardware. Si utilizas un IDE como Eclipse o Arduino
copia dentro de src la carpeta del proyecto.
* *dsn* / *dise�o*: En esta carpeta coloca todos los archivos para el dise�o de tu
proyecto.
  +  *main*: Coloca en esta carpeta los archivos de dise�o original que pueden
incluir, pero no limitarse a: Dibujos 2D, dise�os 3D, archivos CAD, bibliotecas
de componentes, dibujos t�cnicos adicionales.
  +  *aux*: Coloca en esta carpeta los archivos de dise�o auxiliares que ayuden
a construir tu proyecto. Los archivos de dise�o secundario pueden inclu�r dise�os
2D o 3D en formato de intercambio, dibujos t�cnicos adicionales, formatos listos
para manufactura, artes gr�ficos adicionales.
* *extra*: Esta carpeta es libre, aqu� puedes colocar otros archivos que se
puedan requerir para hacer funcionar o construir tu proyecto. Un ejemplo de ello
puede ser un driver controlador de un dispositivo espec�fico o v�nculos a software
relevante, fotograf�as o videos.

Excepci�n de responsabilidades
==============================

Es recomendable que incluyas un texto como el siguiente en tus proyectos:

> El presente proyecto se comparte "tal cual" con el �nico objetivo de que sea �til.
El/los creadores del presente hardware y su software asociado no pueden garantizar su
correcto funcionamiento bajo ninguna circunstancia. El/Los autor/es de este proyecto
no podr�/n hacerse responsable/s de cualquier p�rdida de car�cter material, personal o
econ�mico a su persona o terceros derivados de la utilizaci�n del mismo. Este proyecto
no deber� ser utilizado bajo ninguna circustancia en sistemas de car�cter cr�tico
o sistemas de los cuales dependan vidas de personas de manera directa o indirecta.


Licenciamiento
==============

Agrega aqu� la licencia que utilizas en el c�digo fuente de tu proyecto, adicionalmente
agradecer�amos si colocas la nota de atribuci�n de la plantilla al final.

> La plantilla de este README.md ha sido desarrollada por la comunidad openhardware.sv
con el objetivo de facilitar la documentaci�n de proyectos. Esta plantilla est� protegida
bajo la licencia CC BY, puedes modificarla y redistribuirla manteniendo esta nota de
atribuci�n del autor.
