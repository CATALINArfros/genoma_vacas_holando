# Propuesta de Proyecto “Análisis del genoma bovino en vacas de la raza Holando”

El conjunto de datos que se encuentra en la planilla electrónica con nombre “tablaGENOTIPOSsnps_7748.xlsx”, contiene información de un experimento realizado en Uruguay, que involucró el genotipado de una serie de vacas de la raza Holando. Para el genotipado se utilizó el chip “BovineHD BeadChip” de la empresa Illumina (https://www.illumina.com/Documents/products/datasheets/datasheet_bovineHD.pdf) y el juego de datos de este ejercicio es un subconjunto del mismo, con marcadores elegidos al azar. 

El objetivo de este proyecto consiste en describir de la mejor manera posible características genéticas poblacionales de estas vacas a partir de la información en el experimento. Se puede utilizar cualquier software para el análisis del mismo, pero dependiendo de los conocimientos de los alumnos las opciones más directas son el uso de planillas numéricas electrónicas (Excel, OpenOffice, Numbers, etc.) o directamente en el lenguaje R.

Algunas preguntas y comentarios que pueden ayudar a organizar el proyecto y la redacción de los resultados (sin ser excluyente de otras alternativas):

-	Describir la tecnología usada, incluyendo el chip utilizado (tipo de marcadores, cantidad de los mismos, distribución, criterios para elegirlos, especies que cubre, tipos de razas, etc.).

-	¿Qué proporción de marcadores tiene el juego de datos en relación al total del chip?


-	 ¿Cuál es la distribución de marcadores por cromosoma en el juego de datos? ¿Es representativa del tamaño de los cromosomas bovinos? Utilizar información pública, por ejemplo https://ccb.jhu.edu/bos_taurus_assembly.shtml 

-	¿Cuántos animales fueron genotipados en el juego de datos?

-	¿Qué representa cada una de las columnas del juego de datos?

-	¿Cuántos datos faltantes hay en los genotipados? ¿Cómo es la distribución del score de calidad?

-	Calcular para cada loci el contenido G+C observado (proporción de bases G o C del total de bases genotipadas. Utilizando esa información, describir para cada cromosoma el contenido G+C (por ejemplo, utilizando estadísticos resumen, histogramas, boxplots, etc.)

-	Calcular para cada animal la proporción de loci heterocigotas.

-	Para cada locus crear 3 columnas que describan el conteo de cada uno de los 3 genotipos posibles.


-	Calcular para cada locus la frecuencia relativa de genotipos heterocigotas observada. Describir la heterocigosidad del conjunto de animales a partir de estas frecuencias relativas (por ejemplo, utilizando estadísticos resumen, histogramas, boxplots, etc.).

-	Calcular para cada locus las frecuencias alélicas y las frecuencias esperadas para los 3 genotipos si el locus se encontrase en equilibrio de Hardy-Weinberg.


-	Realizar para cada locus una prueba de chi-cuadrado y determinar si se encuentra en equilibrio de Hardy-Weinberg considerando un alfa=0,0001 (0,01%).

-	Describir la frecuencia del alelo mayor en los datos.
