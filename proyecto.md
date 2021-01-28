# Equipo 06
## Integrantes

**García Gómez Christian Rodrigo**

**García Salman Aldo**

**Olvera Martínez Jennifer Erzsebet**

**Rodríguez Ferrer Azul Itania**

**Ruiz López Jorge Antonio**

**Sánchez Lara Luis Enrique**

# Redes neuronales

# Introducción  
El [genoma humano](https://www.genome.gov/es/genetics-glossary/Genoma) son un conjunto de instrucciones que se encuentran codificadas en bases nitrogenadas (A, C, T, G) y que componen a nuestro ADN, el cual está empaquetado en 23 cromosomas, en el núcleo de nuestras células. 

Si observamos a nuestro alrededor, podremos darnos cuenta que todas las personas son muy diferentes entre sí; esto se debe a los polimorfismos genéticos, en especial, al [polimorfismo de nucleótido único](https://www.genome.gov/es/genetics-glossary/Polimorfismos-de-nucleotido-%C3%BAnico) (SNP).

Los SNPs son sitios del genoma en los que se producen variaciones en un solo par de bases, es decir, a pesar de que los seres humanos compartimos gran parte de la secuencia de ADN, habrá sitios en donde una persona pueda tener una C y otra puede tener una T. Estas diferencias, van a pemritir una expresión del [genotipo](https://www.genome.gov/es/genetics-glossary/Genotipo#:~:text=Un%20genotipo%20es%20la%20colecci%C3%B3n,prote%C3%ADnas%20y%20mol%C3%A9culas%20de%20ARN), en donde los genes son utilizados para fabricar proteínas o moléculas de ADN. 
Su expresión contribuye a observar diferentes caracteristicas entre los individuos ([fenotipo](https://www.genome.gov/es/genetics-glossary/Fenotipo)), por ejemplo, que una persona tenga el cabello lacio y otra lo tenga ondulado. 

Una red neuronal, es un modelo matemático que trata de simular el método de aprendizaje que se lleva a cabo en el cerebro. Cada red está compuesta por neuronas que, a su vez, están conectadas entre ellas.


Como hemos visto, el genoma puede ser representado como un conjunto de datos, por lo que podemos construir una red neuronal capaz de interpretar y clasificar esos datos en diferentes clases de genotipos.


# Objetivo
- Entrenar una red neuronal que sea capaz de clasificar los información genética (SNPs) en genotipos. 

# Hipótesis

A partir de una lista que contiene SNPs, podemos construir una red neuronal que pueda interpretar y clasificar estos datos, para después poder analizarlos de una manera más fácil. 

# Diagrama de metodología

# Métodos

Para realizar la red neuronal, utilizamos el archivo de datos genéticos de ManuSporny, que contiene diferentes filas que corresponden a los SNPs y cuatro columnas que clasifican el resto de la información: 

- Rsid: Es una marca que permite identificar a cada SNP. 
- Cromosoma: El número de cromosoma en donde se encuentra el SNP. 
- Posición: Es la posición de la secuencia de DNA en la que se encontró el cambio. 
- Genotipo: Es la variación de un par de bases en un gen en especial, respecto a un DNA de referencia ?

Estos datos fueron proprocionados por la empresa 23andme, quienes extrajeron el DNA de Manus a partir de una muestra de saliva que fue colocada en un chip de genotipado de Illumina OmniExpress Plus Genotyping, que permite detectar alrededor de diez millones de marcadores genéticos. 





