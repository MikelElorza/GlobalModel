# GlobalModel

En repositorio se agrupa el codigo necesario para resolver un modelo global para plasma de hidrogeno. 
En el fichero GlobalModel.py esta la clase GlobalModel, la cual define el problema que se quiere resolver. Para crear un objeto de esta clase es necesario especificar algunos parametros como las dimensiones de la camara de plasma, la temperatura de los iones, la temperatura del gas neutro, el coeficiente de recombinacion del hidrogeno etc. Tambien es necesario añadir una lista con las reacciones que se quieren tener en cuenta. Muchas de estas reacciones se pueden encontrar en Reactions_H.py. Por último, en Ejemplos.ipynb se muestran algunos ejemplos en los que se utiliza esta clase.
