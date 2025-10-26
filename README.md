# EMIT ML Mining - San Juan

Aplicación de modelos de Machine Learning sobre datos hiperespectrales EMIT en el oeste de San Juan (Argentina).  
Realizado como parte de la diplomatura en Python con orientación en Ciencia de Datos.

---

## Descripción
Este proyecto utiliza datos hiperespectrales del sensor **EMIT (Earth Surface Mineral Dust Source Investigation)** para la identificación preliminar de fases minerales en el oeste de la provincia de San Juan.

---

## Objetivo
Explorar el potencial de los datos hiperespectrales para la **detección indirecta de minerales asociados a ambientes mineros**, aplicando dos modelos de Machine Learning sobre las bandas L2A, utilizando como proxies de ground truth los labels de la banda L2B.

---

## Metodología
- Preprocesamiento de bandas EMIT L2A (corrección y selección espectral)  
- Generación de etiquetas basadas en las clases minerales provistas por EMIT  
- Análisis exploratorio y curación de datos  
- Entrenamiento y comparación de dos modelos supervisados:
  - **XGBoost**  
  - **MLPClassifier**  
- Evaluación de métricas de precisión y matriz de confusión  
- Análisis económico simulado  

---

## Resultados
Se lograron clasificaciones preliminares sobre píxeles de 60x60 m, con etiquetas simplificadas según la fase mineral dominante.

---

## Autor
**Hernán Gabriel Rosenfeld**  
Investigador doctoral (CONICET)  
Enfocado en aplicaciones de teledetección, geociencias y minería.
