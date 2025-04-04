# Aprendizaje por CSS de basico a experto :D

Aprenderemos como centrar un div como hacer estilos movil first, expecificidad, position y display, flex y grid.
Ademas de las meda queris y las transition.
Un monto de cosas mas asi que vamo a darle xd....

## Modulo 1

**Aprendimos A usar la expecifidad y el modelo de caja en lo que se refiere al padding, margin, border y el elemento en si mismo. Ademas, implementamos clases CSS y conocimos estilos embebidos(no se como se escribe xd). Por ultimo hicimos usos de Pseudo clases y Pseudo elementos**

## Modulo 2

**Implementamos las medidas px rem em y min-width/heigth. Entendiendo que para min-wodth debemos partir de un tamano base mientras que para el heigth no, sino que le agregamos el min-heigth como medida para que todo el contenido quede dentro siempre. Ademas usamos vh y vw que son medidas relativas que lo que hace es hacer referencia al tamano de ancgo y largo de nuetra pantalla.**


## Modulo 3

**Centramos y manejamos todos los elementos con flexbox para reforzar lo conocimientos. Ademas de los display inline, block e inline-block. De la misma forma, incluimos el concepto de z-index que nos sirve para superponer elementos como dialogos o modale, recordando que el numero que le asignemos al z-index es indiferente pero debemos mantener un orden logicos**

> Contexto de apilamiento: debemos agregar un position: relative antex de usar z-index. Este va aplicado al elemento que queramos cambiarle el z-index.


# Responsive design and mobile first 

Todos nuestros proyectos deben de empezar con un design primeramente mobile y luego ir escalando a desktop. Esto quiere decir que mientras desarrollamos nuestro proyecto tenemos que ir disesandolo como si fuera una app de tlf primeramente y despues ir viendo como se veria en un ordenador.

>La media query No es la mejor práctica 
---------- --------
@media (min-width: 480px){
 ...
}
@media (min-width: 768px){
 ...
}@media (min-width: 1024px){
 ...
}
-------- ----------

**Tambien podemos inyectar un archivo .css distinto desde nuestro html para no tener que cargar todos los disenos en un solo archivo y asi hacer mas optimo nuestro proyecto**

Este podria ser nuestro estilo mobile first:

`<link rel="stylesheet" href="./style.css"> `

Y este el diseno para pantallas de tablets:

`<link rel="stylesheet" href="tablet.css" media="screen and (min-width:768px)">`

Y este para pantallas mas grandes tipo ordenadores:
`<link rel:'stylesheet' href:'./desktop.css' media:'screen and (min-width: 1024px)' />`