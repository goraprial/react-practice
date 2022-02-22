# ¡Bienvenidx a React!
Esta es una lista de ejercicios de básicos para empezar a trabajar con React.
¡Buena suerte!
## Inicialización de un proyecto React
Para crear un proyecto de React debemos posicionarnos con la terminal sobre la carpeta donde queramos guardarlo. 

Una vez en la carpeta ejecutamos el comando:
`npx create-react-app my-app` 
_(Podemos reemplazar _my-app_ por el nombre que queramos asignarle)_
La terminal va a proceder a hacer la instalación del proyecto.


Finalizada la instalación ejecutamos:
`cd my-app` _(o el nombre que le hayamos asignado)_
para movernos a la carpeta que npx creó, si contamos con vs code podemos hacer:
 `code .` para abrir una instancia de vs code en ese _"path"_ o dirección.

Volvemos a la terminal y **posicionados sobre la ruta del proyecto** hacemos:
`npm i` para que se nos instale la carpeta de _node-modules_ junto con las dependencias y librerías que trae React

#### Levantar la aplicación
Finalmente podremos levantar la aplicación con:
`npm start` lo que abrirá una página por defecto en _http://localhost:3000/_ para poder ver los cambios que hagamos en el código de manera simultanea.

>Para más información sobre la instalación con npx y npm se puede consultar la siguiente documentación: 
>- https://create-react-app.dev/docs/getting-started
>- https://docs.npmjs.com/cli/v6/commands/npm




---
### Ejercicio 1 - *Hello World* 
- Se pide crear una página web donde se muestre **"Hola mundo"** por consola
- Crear una variable **message** que contenga el string 'Hola mundo'
- Hacer que se muestre por consola esta variable 
- Eliminar el console log y renderizar el mensaje en la página por medio de JSX
