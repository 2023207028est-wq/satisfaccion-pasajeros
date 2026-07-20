# Predicción de la satisfacción de pasajeros

Proyecto de Machine Learning que clasifica pasajeros en tres niveles:

- Satisfecho
- Neutral
- Insatisfecho

El proyecto sigue la metodología **CRISP-DM** e incluye análisis exploratorio, preparación de datos, comparación de modelos, evaluación y despliegue mediante ONNX.

## Resultados principales

- **Modelo seleccionado:** Random Forest
- **Exactitud del modelo completo:** 93.16%
- **ROC AUC ponderado:** 99.13%
- **Exactitud del simulador ONNX:** 89.49%
- **Categoría con mayor dificultad:** Neutral

## Dashboard interactivo

[Ver dashboard en ObservableHQ](https://observablehq.com/d/f8ba20577765f6e3)

## Estructura del proyecto

```text
data/       Dataset original y archivos CSV
models/     Modelo entrenado en formato ONNX
notebooks/  Desarrollo completo del proyecto
```

## Clonar el proyecto

```bash
git clone https://github.com/2023207028est-wq/satisfaccion-pasajeros.git
cd satisfaccion-pasajeros
```

## Instalación

```bash
python -m venv .venv
```

En Windows:

```powershell
.venv\Scripts\activate
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecución

```bash
jupyter notebook notebooks/01_airline_satisfaction.ipynb
```

## Fuente

[Customer Satisfaction — Kaggle](https://www.kaggle.com/datasets/johndddddd/customer-satisfaction/data?select=satisfaction.xlsx)

La cobertura geográfica no está especificada en la fuente consultada.

