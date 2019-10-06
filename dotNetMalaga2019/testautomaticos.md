# El framework perfecto para _testing_

## Automatización de tests

La automatización es crear un proceso con la mínima asistencia posible. El test automatizado es y debe ser complementario a otros tipos de tests en nuestros proyectos.

Hay dos principios que debemos perseguir a la hora de realizar testing:

* _Early testing_: realizar tests desde el primer día, o lo más temprano posible.
* _Fail-fast testing_ : encontrar los errores lo antes posible y solventarlos.

Si no seguimos estas prácticas, el tiempo hará que la solución a estos problemas sea largo y costoso, no solo en tiempo si no también en dinero.
Con test automatizados, podemos alcanzar de forma más sencilla estos dos conceptos.

El testing debería ser integrado, no solo una fase que cumplimos cada cierto tiempo.

Por suerte o desgracia, no siempre hay tiempo y recursos para ejecutar todos los tests que contempla nuestra aplicación o proyecto. Es necesario evaluar para priorizar según estos par´metros: criticidad, tiempo, coste, tedio...

Al final, lo que perseguimos es obtener el mayor beneficio empleando el menor esfuerzo.

## El framework de testing perfecto

Elegir o construir el framework para automatizar perfecto es vital para empezar.

Existen muchas herramientas en el mercado, librerías para ejecutar tests y generar reportes eficientes, que generen información de calidad.
Siendo que hay tantas, hay que evaluarlas por:

* Expectativas generadas
* Coste de la herramientas
* Las habilidades necesarias para usarlas
* La formación que necesitará el equipo para utilizarlas

Una vez elegidas las herramientas, modulariza para todas las partes que tenga tu aplicación.
Por capas, partes comunes y partes específics, bien divididas. El orden es clave.

### Behaviour Driven Development

BDD o Behaviour Driven Development es un proceso de desarrollo que promueve la colaboración y testeo entre roles técnicos y no técnicos.

Expone una situación desde un punto de vista concreto que persigue un objetivo, siguiendo [el formato Gherkin](https://cucumber.io/docs/bdd/better-gherkin/). Consiste en generar pruebas siguiendo la siguiente estructura:

* _as a_: ¿qué rol tiene la persona que va a realizar la acción?
* _I want_: ¿qué pretende conseguir?
* _so that_: ¿qué beneficio o efecto genera?

Una vez creado el escenario, podemos especificar:

* _given_: ¿cuál es el contexto inicial desde el cual se parte?
* _when_: ¿qué evento produce el escenario que queremos describir?
* _then_: ¿qué resultado genera?

Si hay muchos puntos que abordar o demasiados tests, siempre se pueden dividir creando escenarios y pasos de negocio. Divide y vencerás por organización.

Entonces... ¿cómo empiezo?

* Crea una PoC
* Contempla el progreso y los tiempos de implementación
* Recuerda que no es una carrera de fondo, llevará su tiempo.

---  

* [Volver al índice](../README.md)

* [Volver al dotNetMálaga2019](./dotNetMalaga2019.md)
