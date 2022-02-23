**Consejos para antes de empezar:**

  _Para no complicarnos realizar los pasos del ejercicio de forma ordenada, item por item._
  
   _Revisar los nombres de las funciones y las variables, que sean auto explicativas._ 
  
  _Cada vez que finalizamos un ejercicio hay que priorizar emprolijar el código lo más que se pueda, tener en cuenta que tiene que ser entendible para alguien más._
  
  
  ---
### Ejercicio 1 - *Hello World* 
- Se pide crear una página web donde se muestre **"Hola mundo"** por consola
- Crear una variable **message** que contenga el string 'Hola mundo'
- Hacer que se muestre por consola esta variable 
- Eliminar el console log y renderizar el mensaje en la página por medio de JSX
### Ejercicio 2 - *Alert button* 
- Crear un botón que al tocarlo muestre la alerta _"Has presionado el botón"_
- Hacer otros 2 botones, cada uno de los tres botones tiene que dar el mensaje _"Has presionado el botón x "_
> Tip: usar la función de js **alert( )**
### Ejercicio 3 - *Props*
Vamos a reutilizar los botones del ejercicio anterior. 

- La función que genera la alerta debe ser una sola y se le debe enviar por props la propiedad **value**, así cada button hace uso de una sola función. Para empezar basta con que cada vez que llamamos al alert diga _"Has presionado el botón"_
- Para darle uso a la propiedad que le enviamos a la función, pasarle al alert la variable **value** de tal manera que ahora cuando se toque un botón nos diga _"Has presionado el botón x"_
### Ejercicio 4 - *Components*
- Crear un componente aparte de App, por ahora lo vamos a hacer Hermano de App, este deberá llamarse **AlertButton** y es necesario importarlo en App. Toda la lógica del botón hay que moverla al nuevo componente y desde App solo llamar al Tag `<AlertButton/>` tres veces para tener los 3 botones originales. 
