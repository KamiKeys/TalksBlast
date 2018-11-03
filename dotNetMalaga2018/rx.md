# be ReactiveX, my friend

La programación reactiva, aplicada con ReactiveX o Rx, es un paradigma de programación para aplicaciones asíncronas, donde los eventos y datos son tratados como un flujo.

Rx.NET es la implementación de Microsoft, pero muchos lenguajes también tienen la propia.

Añadir Rx a nuestro proyecto .NET es tan fácil como:

`using System.Reactive;`

Un Observador, que implementa la interfaz `Observer`, es un emisor sobre el que vamos añadiendo capas, operadores, para tratar esos datos que nos llegan como flujo, como un pulso.

Cuando nos encontramos con Rx, pasamos del `pull model`, donde solicitamos los datos, al `push model`, donde simplemente esperamos a que los datos lleguen y **reaccionamos** a ellos.

## Sigue leyendo:

* [ReactiveX.io](http://reactivex.io/)
* [Implementaciones por lenguaje](http://reactivex.io/languages.html)
* [Swagger editor](https://swagger.io/tools/swagger-editor/)

---  
* [Volver al índice](../README.md)
* [Volver al dotNetMálaga2018](./dotNetMalaga2018.md)