# 02_Modelos

Esta carpeta contiene los modelos entrenados y sus resultados.

## Modelos (.pkl)

Modelos serializados con joblib:

- `modelo_forma1_xgboost_20260128_004102.pkl`
- `modelo_forma1_xgboost_20260128_134753.pkl`
- `modelo_forma1_xgboost_20260128_164122.pkl`

**Formato:** Pickle (joblib)  
**Algoritmo:** XGBoost Regressor  
**Mejor R²:** 0.4605

## Resultados (.csv)

Resultados de evaluación de cada modelo:

- `resultados_forma1_20260128_004102.csv`
- `resultados_forma1_20260128_134753.csv`
- `resultados_forma1_20260128_164122.csv`

**Contienen:**
- Métricas de desempeño (R², MAE, RMSE)
- Comparación entre modelos
- Tiempos de entrenamiento

## Uso

```python
import joblib

# Cargar modelo
modelo = joblib.load('modelo_forma1_xgboost_[fecha].pkl')

# Hacer predicción
prediccion = modelo.predict(X_test)
```

---

**Autor:** Teresa Luna Ramírez  
**Proyecto:** TFM - Predicción Saber Pro
