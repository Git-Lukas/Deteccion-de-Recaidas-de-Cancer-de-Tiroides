# Detección de Recaídas de Cáncer de Tiroides

Estudio realizado en el Máster Universitario Oficial en Gestión y Análisis de Grandes Volúmenes de Datos: BIG DATA.

Universidad Europea Miguel de Cervantes.

**Lucas Todarello.**

## Descripción del contenido del repositorio

- `notebook.ipynb`: Código referente al análisis, resultados y predicción.

- `Cancer_Tiroides.csv`: Dataset etiquetado.

- `diagnostico.csv`: Dataset sin etiquetar.

- `prediccion.csv`: Dataset etiquetado con la predicción calculada.


## Resumen

**Introducción:** El cáncer de tiroides es un tumor o crecimiento malignizado localizado dentro de la glándula tiroides y derivado de células tiroideas que pueden ser foliculares o células C.
En algunos casos cuando un paciente es intervenido de cáncer de tiroides, tiempo después se observa que el tumor aparece de nuevo. En estos casos podemos hablar bien de persistencia o bien de recidiva. La recidiva es la reaparición del tumor tras un periodo más o menos largo con ausencia de enfermedad.

**Métodos:** El objetivo de este estudio es entrenar y optimizar mediante validación cruzada cinco modelos de clasificación. El modelo con el mejor desempeño se utilizará para analizar datos de nuevos pacientes sin etiquetar (sin diagnosticar), con el fin de predecir posibles recurrencias al cáncer de tiroides. Lo que permitirá mejorar la capacidad de detección temprana y el tratamiento adecuado de esta enfermedad.

**Resultados:** El mejor clasificador es el árbol aleatorio(random forest) con una precisión en validación de 0.954 y un Recall del 88% para los casos de recurrencia.

**Conclusiones:** En conclusión, después de evaluar cinco modelos de clasificación en este estudio, se observa que los árboles de decisión logran una puntuación por encima del 90%, destacando especialmente el árbol aleatorio (Random Forest) que combina el método 'baggin' con la aleatoriedad de características mejorando la precisión en el conjunto de prueba a casi un 96%.