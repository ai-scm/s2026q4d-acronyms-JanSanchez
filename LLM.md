# Un LLM (Large Language Model) es un modelo de lenguaje de gran tamaño

Modelos de aprendizaje profundo muy grandes que se pre entrenan con grandes cantidades de datos.

El Transformador subyacente es un conjunto de Redes neuronales que consta de un Codificador y un Descodificador con capacidades de autoatencion, entonces el codificador y el descodificador se encarga de extraer significados de una secuencia de texto y comprenden las relaciones entre las palabras y las frases que contiene

Los transformadores LLM son capaces de entrenarse sin supervision puesto que llevan a cabo un autoaprendizaje, con este proceso los tranformadores aprenden a entender la gramatica, los idiomas y conocimientos basicos

Anteriormente se procesaban con Redes neuronales concurrentes, estos procesaban las entradas de forma secuencial, los transformadores procesan secuencias enteras en paralelo, lo que hace que se puedan utilizar las GPU para entrenar LLMs basados en transformadores

Esta arquitectura de las redes neuronales del trasnformador permist el uso de modelos muy grandes, con cientos de miles de millones de parametros y pueden incorporar cantidades masivas de datos

En el como funciona el LLM antiguamente se utilizaba una tabla numerica para representar cada palabra, pero no podia reconocer las relaciones entre palabras, y se supero usando vectores multidimensionales denominados incrustaciones de palabras, para poder representar palabras de modo que las palabras con significados contextuales similares u otras relaciones esten cerca unas de otras en el espacio vectorial