# ExploraProfit: Análisis de Beneficio y Riesgo para la Expansión de Pozos en OilyGiant
Proyecto de Programa Educativo(Triplete):
## Descripción del Proyecto academico

Trabajas en la compañía de extracción de petróleo OilyGiant. Trabajo es encontrar los mejores lugares donde abrir 200 pozos nuevos de petróleo.

Tienes datos sobre muestras de crudo de tres regiones. Ya se conocen los parámetros de cada pozo petrolero de la región. Crea un modelo que ayude a elegir la región con el mayor margen de beneficio. Analiza los beneficios y riesgos potenciales utilizando la técnica bootstrapping.

## Condiciones
Solo se debe usar la regresión lineal para el entrenamiento del modelo.

Al explorar la región, se lleva a cabo un estudio de 500 puntos con la selección de los mejores 200 puntos para el cálculo del beneficio.

El presupuesto para el desarrollo de 200 pozos petroleros es de 100 millones de dólares.

Un barril de materias primas genera 4.5 USD de ingresos. El ingreso de una unidad de producto es de 4500 dólares (el volumen de reservas está expresado en miles de barriles).
Después de la evaluación de riesgo, mantén solo las regiones con riesgo de pérdidas inferior al 2.5%. De las que se ajustan a los criterios, se debe seleccionar la región con el beneficio promedio más alto.

## Herramientas y Tecnologías
- **Python**: Para análisis y modelado de datos.
- **Pandas & Numpy**: Para la manipulación y análisis de datos.
- **Scipy**: Para analisis estadistico 
- **Scikit-learn**: Para la creacion del modelo de predicion de regresion lineal 