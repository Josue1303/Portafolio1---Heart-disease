# Portafolio 1 - Heart-disease

## Proyecto de Machine Learning: Análisis de Enfermedades Cardíacas

Este proyecto forma parte de mi portafolio del módulo de Machine Learning, en el cual desarrollé modelos de regresión logística utilizando un dataset que contiene información relacionada con enfermedades cardíacas. Durante el análisis, trabajé inicialmente con la columna **ChestPain** como la variable objetivo (label), la cual clasifica los tipos de dolor en el pecho. Sin embargo, posteriormente me di cuenta de que la columna principal a analizar era **target**, la cual indica si un paciente tiene una enfermedad cardíaca (1) o no (0).

A pesar de este ajuste en la selección de la variable objetivo, decidí conservar ambos modelos en el proyecto. Esto me permitió realizar un análisis comparativo y extraer conclusiones relevantes para cada uno de los casos:

- **Modelo con ChestPain como label:** Analiza la capacidad del modelo para predecir el tipo de dolor en el pecho basándose en las características proporcionadas en el dataset. Este análisis es útil para entender cómo se relacionan las características con diferentes manifestaciones de dolor en pacientes con posible riesgo cardíaco.
  
- **Modelo con target como label:** Enfocado en predecir si un paciente tiene o no una enfermedad cardíaca. Este es el análisis principal y el más relevante para la detección temprana de enfermedades cardíacas en pacientes.

Ambos modelos están disponibles en este repositorio, y puedes explorar los notebooks asociados para revisar las metodologías empleadas, los resultados obtenidos y las conclusiones derivadas de cada análisis.

Sientete libre de revisar ambos enfoques para comprender mejor las distintas perspectivas que se pueden adoptar al trabajar con datos de salud.
