# Deep Learning

* Artificial inteligence: Técnicas que permiten a las maquinas parecerse a humanos.
* Machine learning: Metodos estadisticos que permiten a un algoritmo mejorar a lo largo del tiempo.
* Deep Learning: Un tipo de algoritmos que usan redes neuronales como muchas capas. 

Dataset
: Conjunto de los datos con los que contamos para entrenar el algoritmo.

## k-Nearest neighbor

## Red neuronal simple
![Basic Neural Network](./images/simple_nn.png)
### Backward pass
![Backward Pass](./images/backward_pass.png)
Ajusta los valores de la red mientras se ajusta para acercarse mas al valor adecuado. Se modifican los pesos sumando una cantidad aleatoria.

### Forward pass
Se calcula que tan ajustados estan la red a base de los pesos actualmente asignados.

### Activation

# Visión por computadora

## Píxeles
Como se conforma una imagen en la computadora. Contienen un único valor.

Colores:
* Blanco y negro
* Escala de grises
* RGB

## Examen 3

Dataset
: Conjutno de datos completo que tenemos para entrenar al algoritmo

KNN
: K es el numero de elementos cercanos que considera para generar una respuesta

Datapoint
: Una serie de datos que explican un punto del conjunto de datos. Usado para entrenar la red neuronal

Inicialización de pesos (weights)
: Al iniciar una red neuronal los valores iniciales pueden ser generados al azar

Se puede pedir que una red prediga un valor incluso sin pasar aun por la fase de entrenamiento
: Verdadero

Puede ser una muy mala predicción, pero dara un resultado

Para que sirve `.fit()` en Tensorflow neural networks
: Para alimentarle nuestro dataset y asi entrenar la red

Forward Pass
: Se encarga de calcular el valor de salida dependiendo de los pesos actuales

Backward pass
: Modifica los pesos para amoldarse a los datos de salida esperados

Deep Neural Networks
: Similar a una red neuronal simple, pero tiene capas ocultas para inferir abstracciones complejas a base de los datos dados

Función de activación
: Función por la que pasa el resultado de una capa antes de ser entregado al nodo de la capa siguiente, ayuda a simplificarlo

Abstracción *(abstracciones complejas)*
: Una caracteristica que inferimos a base de otras caracteristicas

Epocas (epochs)
: Se Conoce como la cantidad de veces que se realiza en la red el *forward pass* y *backward pass* en nuestro modelo

val_loss
: Es el error que hay al predecir, no usa los datos con los que fue entrenado

loss
: Calcula el error con los datos con los que fue entrenado

Normalización
: Nos sirve para simplificar los datos y hacer más facil para la red ajustart los valores de los pesos

De que se conforma un dataset en las redes neuronales 
: Se conforma de caracteristicas(features) y el resultado esperado (labels) de cada datapoint

Pasos para entrenar una red neuronal
: 
1.  Se inicializa el modelo
2. Se hace un forward pass
3. Se hace un backward pass
4. Se repiten los passes hasta ajustar a un valor correcto o error mínimo

