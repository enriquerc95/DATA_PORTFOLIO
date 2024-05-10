# Análisis de Datos de Powerlifting

## Descripción
Este proyecto, explica en que consiste el Powerlifting y además analiza datos recopilados de competiciones de powerlifting que pertenecen a la asociación Open Powerlifting , explorando tendencias y comparando marcas, edades y atletas.

## Archivos
  ```'df_power = pd.read_csv("../data/raw/openpowerlifting-2023-12-16-fb2308df.csv")' ```: Contiene el dataset.

## Tecnologías Utilizadas
- Python
- numpy 
- Pandas
- Matplotlib
- Seaborn

## Proyectos
-Expllicar en que consiste el powerlifting

-Demostrar que el que tiene más puntuación en Goodlifts, no es necesariamente el más fuerte en todas las marcas.

-Comprobar si hay una mejora en marcas a lo largo de los años. También comprobar si a medida que pasan los años, los jóvenes destacan más con sus marcas.

-Comprobar si es relevante la edad del sujeto en cada categoría.

-Descubrir si en relación peso corporal, hay mucha diferencia entre marcas de una categoría de peso a otra, es decir, comprobar  el ratio de cuantas veces levanta su propio peso los mejores atletas profesionales en relación su peso corporal y sexo.



## Resultados
-Se demuestra que el que tiene más puntuación, no es el más fuerte en todas las marcas.

-No hay una mejora  de marcas a lo mlargo de los años, ya que hay picos en años anteriores de competidores puntuales que se salen de la media. Y en cierto modo, los jóvenes destacan más con sus marcas que años atrás. Los registros muestran un pico en 2019 y 2020.

-La edad del sujeto no es relevante en cierto modo. Aunque el pico generalmente es entre 30 y 40 años. A más de 40 años, las marcas son menos relevantes y como hemos visto, hay jóvenes con marcas superiores a personas con más años compitiendo en estas federaciones.

-Los atletas más pesadostienen mejores marcas, pero no tiene por que ser más fuertes que atletas de menos peso, ya que se demuestra el ratio en atletas menos pesados, que mueven más respecto su peso corporal.


## Bibliografia
Los datos han sido sacados de [Open powerlifting](https://www.openpowerlifting.org), la información de [Información IPF](https://www.powerlifting.sport/fileadmin/ipf/data/rules/technical-rules/spanish/Reglamento_Tecnico_IPF_2023_ESP_2022-11-26.pdf) y de [Fit Generation](https://fitgeneration.es/blog/).

*