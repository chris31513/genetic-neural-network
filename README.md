# Clasificación de genotipos del ser humano, a partir de una red neuronal

## Nombres:

**Aldo Iván García Salman**

**Azul RF ()**

**Christian Rodrigo García Gómez**

**Jennifer OM ()**

**Jorge Antonio Ruiz López**

**Luis SL ()**

# Introducción

El [genoma humano](https://www.genome.gov/es/genetics-glossary/Genoma) son un conjunto de instrucciones que se encuentran codificadas en bases nitrogenadas (A, C, T, G) y que componen a nuestro ADN, el cual está empaquetado en 23 cromosomas, en el núcleo de nuestras células. 

Si observamos a nuestro alrededor, podremos darnos cuenta que todas las personas son muy diferentes entre sí; esto se debe al [polimorfismo de nucleótido único](https://www.genome.gov/es/genetics-glossary/Polimorfismos-de-nucleotido-%C3%BAnico) (SNP).

Los SNPs son sitios del genoma en los que se producen variaciones en un solo par de bases, es decir, a pesar de que los seres humanos compartimos gran parte de la secuencia de ADN, habrá sitios en donde una persona pueda tener una C y otra puede tener una T. Estas diferencias, van a pemritir una expresión del [genotipo](https://www.genome.gov/es/genetics-glossary/Genotipo#:~:text=Un%20genotipo%20es%20la%20colecci%C3%B3n,prote%C3%ADnas%20y%20mol%C3%A9culas%20de%20ARN), en donde los genes son utilizados para fabricar proteínas o moléculas de ADN. 
Su expresión contribuye a observar diferentes caracteristicas entre los individuos ([fenotipo](https://www.genome.gov/es/genetics-glossary/Fenotipo)), por ejemplo, que una persona tenga el cabello lacio y otra lo tenga ondulado. 

- Red neuronal

Una red neuronal, es un modelo matemático que trata de simular el método de aprendizaje que se lleva a cabo en el cerebro. Cada red está compuesta por neuronas que, a su vez, están conectadas entre ellas.

- Neurona

Cada neurona es una función matemática aplicada a una combinación lineal de las entradas xi con los pesos wi, cada peso está asociado a una conexión con la neurona ni. 
Matemáticamente la neurona se vería así:

![equation] a_i = f(\sum w_ix_i)

Siendo ai el valor de activación de la neurona.

- Funciones de activación

Dentro del mundo de la probabilidad y la estadistica, existen diferentesfunciones que son usadas para representar la activaci ́on de las neuronas.La funci ́on usada en nuestra red es la funci ́on ReLu, que es m ́ascomunmente usada en redes convolucionales.  Sin embargo en nuestrosexperimentos result ́o ser la m ́as eficaz.Su formulaci ́on matem ́atica es la siguiente:


Como hemos visto, el genoma puede ser representado como un conjunto de datos, por lo que podemos construir una red neuronal capaz de interpretar y clasificar esos datos en diferentes clases de genotipos.



# Objetivo

- Entrenar una red neuronal que sea capaz de clasificar la información genética proprocionada (SNPs) en genotipos.

# Hipótesis

- A partir de una lista que contiene SNPs, podemos construir una red neuronal que pueda interpretar y clasificar estos datos, en diferentes clases de genotipos.

# Diagrama metodológico

# Resultados

# Conclusiones

# Referencias 


Objetivo: Lograr entrenar una red neuronal para que sea capáz de clasificar información genética en genotipos.

Hipótesis: Las redes neuronales son un conjunto de algoritmos y heuristicas capaces de predecir, clasificar y distinguir datos. Sabemos que la información genética puede ser representada como un conjunto de datos. Nuestra hipótesis es que podemos construir una red neuronal capáz de interpretar y clasificar esos datos en diferentes clases de genotipos.
