# Introduccion

Este documento corresponde a la primera actividad de python de la asignatura de visualizacion de datos, desarrollado por el estudiante Miguel Jaimes.

El propósito de este documento es aplicar un proceso completo de análisis de datos en Python que incluya la carga, exploración, descripción de variables, visualización y análisis inferencial, con el fin de identificar y comprender la presencia de valores faltantes en el conjunto de datos. A partir de esta detección, se busca investigar los métodos más utilizados para la imputación de datos, evaluar cuál es el más recomendado en función del tipo de variable y del contexto del análisis, y justificar la elección con base en criterios estadísticos y prácticos.

([Fuente de los datos](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv))

Registros: 1338
Campos: 7

Informacion de las variables:
- age: edad en años (numérica).
- sex: sexo biológico (categórica: female, male).
- bmi: índice de masa corporal (numérica).
- children: número de hijos/dependientes (entero).
- smoker: hábito de fumar (categórica: yes, no).
- region: región de residencia (categórica: northeast, northwest, southeast, southwest).
- charges: costo anual del seguro en USD (numérica, variable de interés).

A continuación, el informe:

```{tableofcontents}
```
