
# Predicción de medicación más efectiva para pacientes

## Descripción
Este proyecto busca determinar qué medicamento es más efectivo para pacientes con una misma enfermedad, usando diferentes modelos de machine learning para encontrar la mejor opción según las características de cada paciente.

## Tecnologías utilizadas
- Python
- Orange (software para machine learning)
- Pandas, itertools, random
- Modelos: Árbol de decisiones, KNN, Redes neuronales

## Metodología
1. **Preprocesamiento de datos**: Limpieza y traducción de columnas para mejor comprensión.
2. **División de datos**: 70% entrenamiento, 30% pruebas.
3. **Entrenamiento de modelos**:
   - Árbol de decisiones: **98% de precisión**
   - Redes neuronales: **95% de precisión**
   - KNN: **61% de precisión** (ajustado a 80%, pero sigue por debajo de los otros modelos)
4. **Validación y predicción**: Se probó con nuevos datos, confirmando que el Árbol de Decisiones es el modelo más robusto.

## Resultados finales
- Predicción para el primer paciente: **Medicamento "Y"** (extranjero)
- Predicción para el segundo paciente: **Medicamento "B"** (nacional)

## Posibles mejoras
- Incluir más variables clínicas.
- Optimizar los hiperparámetros de KNN.
- Implementar modelos de ensamble como Random Forest.
