# Aprendizaje Automático

Trabajos prácticos de la materia Aprendizaje Automático de la Tecnicatura en Análisis de Datos e Inteligencia Artificial: métodos supervisados (clasificación y regresión) y no supervisados (clustering).

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| [TP1-Aprendizaje-Automatico.ipynb](notebooks/TP1-Aprendizaje-Automatico.ipynb) | TP principal: predicción de precios de vehículos usados en Argentina (`argentina_cars.csv`) con métodos supervisados. |
| [Claramunt_Federico_10_Clustering_ITSE.ipynb](notebooks/Claramunt_Federico_10_Clustering_ITSE.ipynb) | Métodos no supervisados: clustering (K-Means y método del codo) sobre un dataset público de jugadores. |
| [ApjeAutom_Grupo2_...ipynb](notebooks/ApjeAutom_Grupo2_Claramunt-Federico_Ojo-de-Agua.ipynb) | Entrega grupal: misma problemática de predicción de precios resuelta en equipo. |
| [Claramunt_Federico_..._Examen_set_2026.ipynb](notebooks/Claramunt_Federico_Examen_set_2026.ipynb) | Examen: clasificación sobre el Breast Cancer Wisconsin Dataset (scikit-learn). |

Todos los notebooks se publican ejecutados, con sus salidas y gráficos, y se pueden leer directamente en GitHub.

## Datos

- `data/argentina_cars.csv`: dataset de vehículos usados en Argentina (utilizado por el TP1 y la entrega grupal).
- El notebook de clustering descarga sus datos de una URL pública y el examen utiliza datasets de scikit-learn: no requieren archivos adicionales.

## Cómo ejecutarlos

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook notebooks/TP1-Aprendizaje-Automatico.ipynb
```

Las rutas de datos dentro de los notebooks son relativas a `data/` (los notebooks viven en `notebooks/`).

## Temas cubiertos

- Representación y exploración de datos
- Regresión logística y KNN para clasificación
- Clasificación multiclase
- Árboles de decisión
- Regresión con validación cruzada y ajuste de hiperparámetros
- Métodos no supervisados: clustering (K-Means, método del codo)

## Informes

- `informes/TP1_Aprendizaje_Supervisado.pdf`

## Licencia

MIT
