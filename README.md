# Neural Network for Celsius to Fahrenheit conversion
Este proyecto utiliza una red neuronal simple construida con Python y TensorFlow para aprender a convertir temperaturas de grados Celsius a Fahrenheit.

This project uses a simple neural network built with Python and TensorFlow to learn how to convert temperatures from degrees Celsius to Fahrenheit.

## ¿Por qué una red neuronal? / Why a neural network?
Aunque la fórmula para convertir Celsius a Fahrenheit es bien conocida $$ F = C \times \frac{9}{5} + 32 $$, este proyecto sirve como una introducción práctica a las redes neuronales y el aprendizaje automático. En lugar de programar explícitamente la fórmula, alimentamos a la red neuronal con ejemplos de conversiones correctas y permitimos que la red aprenda la relación por sí misma.}

Because the formula for converting Celsius to Fahrenheit is well known $$ F = C \times \frac{9}{5} + 32 $$, this project serves as a practical introduction to neural networks and machine learning. Instead of explicitly programming the formula, we feed the neural network with examples of correct conversions and allow the network to learn the relationship by itself.

## ¿Cómo funciona? / How does it work?
Las redes neuronales se separan en capas. Cada capa puede tener una o mas neuronas. Cualquier red tiene siempre una capa de entrada (En este caso, los grados celsius que queremos convertir) y una capa de salida (Donde obtendremos el resultado calculado, en este caso los grados fahrenheit resultantes).
Las neuronas se conectan entre capas, y cada conexión tiene un peso. Durante el entrenamiento, la red neuronal ajusta los pesos de las conexiones para obtener el resultado deseado. En este caso, solo tenemos una conexión entre la neurona de entrada y salida la red neuronal ajusta los pesos para obtener la conversión correcta de grados celsius a fahrenheit. El peso es un valor numérico que indica la importancia de la conexión entre dos neuronas.
Cada neurona, a excepción de las de entrada, tiene un sesgo. El sesgo es un valor numérico que se suma a la suma ponderada de las entradas de la neurona. El sesgo permite que la red neuronal aprenda incluso cuando todas las entradas son cero.
Por ultimo, cada neurona tiene una función de activación. La función de activación determina si la neurona se activa o no.

El proceso que sigue la red neuronal para convertir grados celsius a fahrenheit es el siguiente:
- Colocaremos los grados celsius en la capa de entrada, en la primera neurona.
- Estos grados celcius se multiplicarán por el peso de la conexión entre la neurona de entrada y la neurona de salida, luego se sumará el sesgo de la neurona de salida y este será nuestro resultado.
- Finalmente, la función de activación de la neurona de salida se activará y obtendremos el resultado de la conversión de grados celsius a fahrenheit.

The neural networks are separated into layers. Each layer can have one or more neurons. Any network always has an input layer (In this case, the celsius degrees we want to convert) and an output layer (Where we will get the calculated result, in this case the resulting fahrenheit degrees).
The neurons are connected between layers, and each connection has a weight. During training, the neural network adjusts the weights of the connections to obtain the desired result. In this case, we only have one connection between the input and output neuron, the neural network adjusts the weights to obtain the correct conversion from celsius to fahrenheit degrees. The weight is a numerical value that indicates the importance of the connection between two neurons.
Each neuron, except the input ones, has a bias. The bias is a numerical value that is added to the weighted sum of the neuron's inputs. The bias allows the neural network to learn even when all inputs are zero.
Finally, each neuron has an activation function. The activation function determines whether the neuron is activated or not.

The process that the neural network follows to convert celsius to fahrenheit degrees is the following:
- We will place the celsius degrees in the input layer, in the first neuron.
- These celsius degrees will be multiplied by the weight of the connection between the input neuron and the output neuron, then the bias of the output neuron will be added and this will be our result.
- Finally, the activation function of the output neuron will be activated and we will get the result of the conversion from celsius to fahrenheit degrees.

## ¿Cómo ejecutar el proyecto? / How to run the project?
1. Clonar el repositorio
2. Asegúrate de tener instalado Python y TensorFlow.
3. Ejecuta el script principal para entrenar la red neuronal. En este caso es un archivo de Jupyter Notebook (.ipynb) que puedes ejecutar con Jupyter Notebook o Google Colab.
4. Una vez entrenada, puedes usar la red neuronal para convertir temperaturas de Celsius a Fahrenheit.

1. Clone the repository
2. Make sure you have Python and TensorFlow installed.
3. Run the main script to train the neural network. In this case it is a Jupyter Notebook file (.ipynb) that you can run with Jupyter Notebook or Google Colab.
4. Once trained, you can use the neural network to convert temperatures from Celsius to Fahrenheit.

## Contribuciones / Contributions

Las contribuciones a este proyecto son bienvenidas. Si tienes sugerencias para mejorar la red neuronal o el código, no dudes en abrir un issue o un pull request.

The contributions to this project are welcome. If you have suggestions to improve the neural network or the code, feel free to open an issue or a pull request.
