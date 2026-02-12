# 03_Procesamiento

Carpeta reservada para archivos intermedios del preprocesamiento.

## Estado actual

Esta carpeta está vacía porque todo el preprocesamiento 
se realiza dentro del pipeline de scikit-learn en el 
notebook principal, sin generar archivos intermedios.

## Proceso de preprocesamiento

El pipeline incluye:

- **Variables numéricas:** Imputación por mediana + StandardScaler
- **Variables categóricas:** Imputación por moda + OneHotEncoder
- **Framework:** scikit-learn ColumnTransformer

## Uso futuro

Podría utilizarse para:
- Datos preprocesados antes del modelado
- Datasets intermedios durante ETL
- Transformaciones que requieran persistencia

Ver notebook completo en `05_Cuaderno/`

---
**Autora:** Teresa Luna Ramírez | **UNIR 2026**
