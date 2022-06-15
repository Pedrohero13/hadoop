# Hadoop 
## Introducción
Apache Spark es un marco rápido y potente que proporciona una API para realizar un procesamiento distribuido masivo en conjuntos de datos resistentes. La principal abstracción que proporciona Spark es un conjunto de datos distribuido resistente (RDD), que es el tipo de datos fundamental y principal de este motor. Spark SQL es el módulo de Apache Spark para trabajar con datos estructurados y MLlib es la biblioteca escalable de aprendizaje automático de Apache Spark. Apache Spark está escrito en lenguaje de programación Scala. Para admitir Python con Spark, la comunidad de Apache Spark lanzó una herramienta, PySpark. PySpark tiene una velocidad de cálculo y una potencia similares a las de Scala. PySpark es un motor paralelo y distribuido para ejecutar aplicaciones de big data. Con PySpark, puede trabajar con RDD en el lenguaje de programación Python.

### Este tutorial analiza Big Data a través de PySpark, un paquete de Python para la programación de Spark. Las bibliotecas de alto nivel de Spark, como SparkSQL, Mllib, se utilizarán para interactuar con dos conjuntos de datos diferentes.

## ¿Qué es SparkContext?
Spark viene con un shell de python interactivo en el que PySpark ya está instalado. PySpark crea automáticamente un SparkContext para usted en PySpark Shell. SparkContext es un punto de entrada al mundo de Spark. Un punto de entrada es una forma de conectarse al clúster de Spark. Podemos usar SparkContext usando la variable sc. En los siguientes ejemplos, recuperamos la versión SparkContext y la versión Python de SparkContext.

