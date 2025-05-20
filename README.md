# Usuarios y sus compras de alimentos

## Descripción
La empresa de productos alimenticios en la cual trabajamos nos pidio realizar una investigación del comportamiento de los usuarios

## Objetivos
- Preparar los datos
- Realizar análisis exploratorio
- Estudio del embudo de ventas
- Una prueba A/A/B (el cual consiste en 2 grupos de control y 1 de prueba)

## Tecnologias
- Python
- Vs code
- pandas
- math
- datetime
- numpy
- scipy
- matplotlib

## Analisis
- El periodo de prueba es bastante corto de finales de Julio hasta los primeros dias de Agosto alrededor de 13 dias
- Comprobando la frecuencia de las fechas solo se tienen datos significativos a partir del 1 de Agosto del 2019
- Teniendo en cuenta lo anterior se filtro a partir de esta fecha para que sean mas relavante el análisis
- Se verifico que el nuevo dataframe cuenta con 240887 en comparacion al viejo con 243713 por lo cual solo se descartaron 2826 registros
- Se verifico que estuvieran los 3 tipos de usuarios para realizar el análisis A/A/B
- En cuanto al promedio con los datos filtrados se puede ver que no tuvo un cambio significativo
- en los 2 ordenes de eventos mostrados se ve que solo el 2.6% de las persona completo todos los eventos
- en el cual nos centraremos es en el orden (main,offer,cart,payment,tutorial) ya que el tutorial puede ser un evento mas bien totalmente opcional con esto me refiero a que el en el flujo no afecta
- a medida que avanza el flujo de los eventos se ve una disminucion de personas siendo las que completan una compra muy pocas

## Resultados prueba
- No se puede decir que exista una diferencia estadística de los grupos de control

- Las funciones realizan una evaluación por evento entre 2 muestras viendo las proporciones de estas como se puede ver en los experimentos en todo los eventos de los grupos aunque la significancia este en 0.1 o 0.05 no se tiene razon para decir las proporciones entre los eventos de los grupos es diferente

- Segun los datos el experimento aunque tuviera una corta duración se tuvo una proporción casi igual en los diferentes grupos

- Por otro lado los cambios realizados para el experimento parecen no afectar el comportamiento del usuario por lo que se recomienda buscar uno con mayor impacto para realizar ventas.
