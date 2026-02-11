# 01_Datos

Esta carpeta documenta los datos utilizados en el proyecto.

## Nota sobre los datos

Los archivos de datos originales NO están incluidos en este 
repositorio debido a su tamaño (640 MB).

## Fuentes de datos

### Datos nacionales (ICFES)
- **Fuente:** Portal de datos abiertos del gobierno colombiano
- **URL:** https://www.datos.gov.co
- **Búsqueda:** "Saber Pro resultados individuales"
- **Período:** 2019-2024
- **Registros:** 1,217,482 estudiantes
- **Formato:** CSV

### Datos institucionales (UCN)
- **Fuente:** Fundación Universitaria Católica del Norte
- **Estudiantes:** 259 (programa Ingeniería Informática)
- **Nota:** Datos institucionales de acceso restringido

## Variables principales

| Variable | Tipo | Descripción |
|----------|------|-------------|
| `mod_razona_cuantitat_punt` | Numérica | Variable objetivo (0-300) |
| `mod_lectura_critica_punt` | Numérica | Predictor (0-300) |
| `mod_comuni_escrita_punt` | Numérica | Predictor (0-300) |
| `mod_competen_ciudada_punt` | Numérica | Predictor (0-300) |
| `mod_ingles_punt` | Numérica | Predictor (0-300) |
| `fami_estratovivienda` | Categórica | Estrato (1-6) |
| `estu_genero` | Categórica | Género (M/F) |
| `fami_educacionpadre` | Categórica | Nivel educativo padre |
| `fami_educacionmadre` | Categórica | Nivel educativo madre |

## Cómo obtener los datos
```bash
# 1. Ir a datos.gov.co
# 2. Buscar "Saber Pro"
# 3. Descargar resultados individuales 2019-2024
# 4. Guardar en esta carpeta como:
#    datos_saberpro_YYYY.csv
```

## Preprocesamiento

Todo el preprocesamiento se realiza en el notebook principal:
```
05_Notebook/modelo_forma1_COMPLETO.ipynb
```

---

**Autora:** Teresa Luna Ramírez  
**Proyecto:** TFM - Predicción Saber Pro - UNIR 2026
