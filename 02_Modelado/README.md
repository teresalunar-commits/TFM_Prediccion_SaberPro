# 02_Modelado

Modelos entrenados y resultados de evaluación.

## Modelos (.pkl)

| Archivo | Descripción |
|---------|-------------|
| `modelo_forma1_xgboost_20260128_004102.pkl` | Versión 1 |
| `modelo_forma1_xgboost_20260128_134753.pkl` | Versión 2 |
| `modelo_forma1_xgboost_20260128_164122.pkl` | Versión final |

**Algoritmo:** XGBoost Regressor  
**Mejor R²:** 0.4605 | **MAE:** 18.55 | **RMSE:** 24.04

## Resultados (.csv)

| Archivo | Descripción |
|---------|-------------|
| `resultados_forma1_20260128_004102.csv` | Métricas versión 1 |
| `resultados_forma1_20260128_134753.csv` | Métricas versión 2 |
| `resultados_forma1_20260128_164122.csv` | Métricas versión final |

## Cargar modelo
```python
import joblib
modelo = joblib.load('modelo_forma1_xgboost_20260128_164122.pkl')
prediccion = modelo.predict(X_test)
```

---
**Autora:** Teresa Luna Ramírez | **UNIR 2026**
