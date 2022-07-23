# Descripcion del Proyecto React

El siguiente proyecto es una aplicación de cuenta regresiva. El usuario ingresa la cantidad de tiempo para que el reloj funcione y comienza la cuenta regresiva hasta 0.

## Pasos con la aplicación Create React

Este proyecto fue iniciado con [Create React App](https://github.com/facebook/create-react-app).

Para este proyecto necesitamos tener instalado Node Js (https://nodejs.org/es/download/).

A continuacion los siguientes comandos se ejecutan en la terminal de nuestros ordenadores.

### `node --version`
Para comprobar si tenemos node js instalado de manera correcta en nuestro ordenador.

### `npm install create-react-app -g`


### `create-react-app (name-project)`
El siguiente comando es para instalar el proyecto base.


### `cd .\(name-project)\`
Now your project is set up in a new directory.

### `npm start`
Ejecuta la aplicación en modo de desarrollo.
Abrimos en la siguiente direccion [http://localhost:3000](http://localhost:3000) para poder verlo en nuestro navegador de preferencia.


### `npm install react-bootstrap --save`
Incluye React Bootstrap en tu proyecto


## Datos Importantes del Proyecto

* Importación y exportación de ES6: una nueva sintaxis para compartir código entre archivos separados. Se utiliza en casos como `import React from ‘react’`
* Estado - los datos pertinentes a una aplicación. Cada componente tiene su estado local siempre que declare agregar el constructor a un Componente y declare su objeto de estado.
* Estado de actualización: al actualizar el estado, debemos asegurarnos de nunca cambiar el estado de manera directa. Ya que si lo hace, podria causar errores fatales en su aplicación. Para esto es recomendable volver a declarar nuevas instancias de matrices u objetos de estado y tambien usar la función setState() para asi poder actualizar el estado.
* Props: esto es similar al estado, excepto que los datos se heredan del componente principal que especifica las partes del estado como propiedades.
* LifeCycle Methods - eventos en los componentes de React que se activan en casos como renderizado dentro o fuera de la pantalla o tambien durante  las actualizaciones de estado.`componentDidMount()` lifeCycle hook.

## Contact:
Correo Personal: francisalexander99@hotmail.com
Correo Institucional:francis.rios.tupiza@udla.edu.ec
NumeroCelular: 0995630236