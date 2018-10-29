[< Inicio](./README.md)
# DotNet Málaga 2018
## Machine Learning
1. **Inputs** o datos de capacitación son los datos que recibe el modelo. Debemos tener muy claro que datos necesitará nuestro modelo para realizar sus predicciones. Por ejemplo, si nuestro modelo va a predecir el tiempo de llegada a un lugar nuestros _inputs_ serán datos como el tráfico de la zona, el punto de partida, el punto de destino, etc, pero no necesitara datos como el modelo del coche en el que vamos o la marca de las zapatillas que llevaremos para llegar andando a nuestro destino.
2. **Entrenamiento**, se introducen datos en el modelo y se le dice cual es la salida esperada. Debemos disponer de datos suficientes para entrenar nuestro modelo de los cuales deberemos conocer sus _inputs y _outputs_, con el fin de indicarle al modelo como debe predecir en el futuro cuando no se conozcan los _outputs_. En el ejemplo anterior deberiamos conocer el tiempo de llegada de una catidad optima de casos ya conocidos para entrenar el modelo y que preiga de forma eficiente el tiempo de llegada en el futuro con _inputs_ totalmente distintos a los del entrenamiento.
3. **Output** o predicción que dará el modelo una vez entrenado.

Existen **_modelos predefinidos_ que se pueden entrenar para nuestra casuística**, con lo que no tendremos que preocuparnos en construir un complicado modelo de red neuronal para realizar nuestras predicciones.

### Tipos de predicción
+ On-Cloud: El modelo está en e servidor y se accede a el através de peticiones http.
+ On-Device: El modelo se encuentra en el dispositivo, suelen ser más ligeros y menos precisos que los que se encuentran en un servidor, ya que estos disponen de más capacidad de procesamiento.

### ML Kit (Android)
+ Consta de **modelos predefinidos**.
+ Se pueden crear **modelos presonalizados** o **_custom_**.
+ _Oncloud_ y _OnDevice_.

### Core ML (iOS)
+ Solo admite **modelos _custom_**.
+ _Oncloud_ y _OnDevice_.
+ Los modelos _OnDevice_ pueden descargarse desde una URL.

### Enlaces
+ [Azure Conitive Service](https://customvision.ai/)
+ [ML Kit](https://developers.google.com/ml-kit/)(Android)
+ [Core ML](https://developer.apple.com/documentation/coreml)(iOS)
  
---  
[Volver al &iacute;ndice](https://github.com/KamiKeys/TalksBlast/blob/master/README.md)
