# Proyecto Final - Modelos de Lenguaje

Este repositorio contiene el cuaderno principal del proyecto final para el curso de Modelos de Lenguaje. Toda la lógica que antes vivía en scripts de Python se centralizó en el notebook [`notebooks/proyecto_final.ipynb`](notebooks/proyecto_final.ipynb).

## Contenido

- `notebooks/proyecto_final.ipynb`: flujo completo para preparar datos, entrenar y evaluar un modelo basado en Transformers en inglés.
- `data/`: directorio esperado con los conjuntos de datos en formato JSONL (`train.jsonl`, `validation.jsonl`, etc.).
- `models/`: carpeta donde se almacenan los pesos y el tokenizer resultantes del entrenamiento.

## Requisitos

Para ejecutar el notebook se recomienda crear un entorno virtual con Python 3.10 e instalar las dependencias principales:

```bash
pip install pandas datasets transformers
```

## Ejecución

1. Coloca los archivos JSONL en la carpeta `data/`.
2. Abre el cuaderno con Jupyter Lab o VS Code.
3. Ejecuta las celdas en orden para reproducir el entrenamiento y la evaluación.

## Resultados

El entrenamiento generará un modelo ajustado para clasificación de texto en inglés junto con las métricas de evaluación y los artefactos guardados en `models/english-bert-finetuned`.
