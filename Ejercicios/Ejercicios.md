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
- Crear un componente aparte de App, por ahora lo vamos a hacer Hermano de App, este deberá llamarse `AlertButton` y es necesario importarlo en `App`. Toda la lógica del botón hay que moverla al nuevo componente y desde App solo llamar al Tag `<AlertButton/>` tres veces para tener los 3 botones originales. 

### Ejercicio 5 - *Hook UseState*
- Leer la documentación de [Introducción a Hooks](https://reactjs.org/docs/hooks-state.html) y [UseState](https://reactjs.org/docs/hooks-state.html). Recuerden que nosotros vamos a trabajar con **componentes funcionales** y no con componentes de clase.
- Dentro de la carpeta **src** crearemos una carpeta llamada **components** y dentro de esta crearemos un componente llamado `Counter.js`
- La página debe mostrar un texto que diga **"Contador: x"** *(La X será una variable "value" que vamos a manejar con UseState y vamos la vamos a inicializar como "0")*
- Crear un botón debajo que al clickearlo sume **+ 1** a la variable value por medio de `setState` el cual vamos a llamar dentro del evento 
```javascript
onClick={() => (...)}
```
- El texto de la página deberá **actualizarse** cada vez que sumemos un valor más.
- Para finalizar, hacer una función `handleAdd` dentro del componente del contador la cual le asigne un `setState` a nuestra variable y sea llamada por el evento `onClick`
#### Ejemplo
![Peek 07-03-2022 11-32](https://user-images.githubusercontent.com/83319295/157053869-e27764dd-e480-4487-825f-a97f7faad0c6.gif)


