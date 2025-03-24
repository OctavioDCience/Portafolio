# Predicción del PIB de México

## Descripción
Este proyecto crea un modelo de regresión logística para predecir el crecimiento del PIB de México en los próximos años, ajustando los datos históricos mediante mínimos cuadrados y normalización.

## Tecnologías utilizadas
- Python
- Pandas, NumPy, Matplotlib
- Regresión logística

## Metodología
1. **Carga de datos**: Se importan los datos del PIB y se verifican.
2. **Normalización**: Se escalan los datos por el alto volumen de las cifras.
3. **Creación del modelo**: Se entrena una regresión logística ajustada con mínimos cuadrados.
4. **Evaluación**: Se obtuvo un R² de 0.98, mostrando una alta precisión.
5. **Predicción**: Se extiende la proyección hasta 2027.

## Resultados
- Predicción para el año 2022: **1,255,334,744,803.18**
- El modelo demostró ser altamente preciso gracias a la normalización.
- Se superaron los errores iniciales de manejo de grandes cantidades numéricas.

## Posibles mejoras
- Incluir más variables económicas.
- Probar otros modelos como redes neuronales o regresiones polinomiales.
