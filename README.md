Predicción de Rendimiento en Razonamiento Cuantitativo - Saber Pro

**Autora:** Teresa Luna Ramírez  
**Máster:** Análisis y Visualización de Datos Masivos - UNIR  
**Año:** 2025-2026  
**Estado:** Aprobado - Apto para defensa

---

## Resumen

Modelo predictivo para anticipar el rendimiento en Razonamiento 
Cuantitativo del examen Saber Pro en Colombia, aplicando 
metodología CRISP-DM sobre 1,217,482 registros (2019-2024).

## Resultados principales

| Métrica | Valor |
|---------|-------|
| **Mejor modelo** | XGBoost Regressor |
| **R²** | 0.4605 |
| **MAE** | 18.55 puntos |
| **RMSE** | 24.04 puntos |
| **Dataset** | 1,217,482 registros |

---

## Estructura
```
├── 01_Datos/           # Documentación de datos (640MB - no incluidos)
├── 02_Modelado/        # Modelos .pkl y resultados .csv
├── 03_Procesamiento/   # Pipeline de preprocesamiento
├── 04_Figuras/         # 7 visualizaciones (300 DPI)
├── 05_Cuaderno/        # Notebook principal
└── 06_Documentos/      # TFM completo (PDF)
```

---

## Inicio rápido
```bash
# 1. Clonar repositorio
git clone https://github.com/teresalunar-commits/TFM_Prediccion_SaberPro.git

# 2. Instalar dependencias
cd TFM_Prediccion_SaberPro/05_Cuaderno
pip install -r requirements.txt

# 3. Abrir notebook
jupyter notebook modelo_forma1_COMPLETO.ipynb
```

---

## Modelos evaluados

| Modelo | R² | MAE | RMSE |
|--------|-----|------|------|
| **XGBoost** | **0.4605** | **18.55** | **24.04** |
| Random Forest | 0.4533 | 18.79 | 24.19 |
| Ridge/Lasso | 0.4478 | 19.02 | 24.68 |
| Baseline | 0.0000 | 31.17 | 41.04 |

---

## Hallazgos principales

- **Predictor más importante:** Lectura Crítica (r=0.68)
- **Variables académicas:** 83% de importancia total
- **Variables sociodemográficas:** 17% de importancia
- **Desempeño UCN:** Superior a media nacional
- **Contexto:** Análisis a escala nacional Colombia

---

## Privacidad y ética

- Datos públicos y anonimizados (ICFES)
- Cumple RGPD y Ley 1581/2012 Colombia
- Sin identificación individual

---

## Licencia

MIT License - Ver archivo `LICENCIA`

---

**© 2026 Teresa Luna Ramírez - UNIR**
