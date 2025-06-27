# Modelo de Accesibilidad para Personas Mayores

Este proyecto tiene como objetivo desarrollar un modelo basado en visión por computadora que analice imágenes de espacios físicos y estime una métrica de accesibilidad orientada a personas mayores.

## Objetivo

Detectar características en imágenes de entornos (interiores o exteriores) que influyan en la accesibilidad para personas mayores, y asignar una métrica que refleje su nivel de adecuación.

## Enfoque

- Preprocesamiento y análisis de imágenes.
- Entrenamiento de un modelo de clasificación o regresión.
- Cálculo e interpretación de una métrica de accesibilidad.
- Evaluación y validación sobre un conjunto de datos representativo.

## Estructura del Proyecto

```

modelo-accesibilidad-mayores/
├── README.md
├── requirements.txt
├── .gitignore
├── data/                  # Imágenes y datasets
├── src/                   # Código fuente
│   ├── preprocesamiento.py
│   ├── modelo.py
│   └── inferencia.py
└── notebooks/             # Exploración y experimentación
    └── exploracion.ipynb

````

## Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/modelo-accesibilidad-mayores.git
   cd modelo-accesibilidad-mayores
   ```

2. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutar notebook de exploración o scripts de entrenamiento.

