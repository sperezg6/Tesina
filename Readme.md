# Modelado y Generacióon
Musical: Una Aproximación
Mediante Redes Neuronales y
Entradas MIDI 

Este proyecto implementa un pipeline completo para el análisis, modelado y generación de música a partir de archivos MIDI utilizando técnicas de deep learning, principalmente redes LSTM.

## Estructura del Proyecto

- **Procesamiento de datos:** Extracción de notas, acordes y características musicales de archivos MIDI usando `pretty_midi` y `music21`.
- **Análisis exploratorio:** Estadísticas descriptivas, visualización de distribuciones de notas, acordes, duración, polifonía, etc.
- **Preprocesamiento:** Filtrado de instrumentos, eliminación de notas poco frecuentes, codificación y preparación de secuencias para entrenamiento.
- **Modelado:** Entrenamiento de modelos LSTM y Bidirectional LSTM para la generación de secuencias musicales.
- **Evaluación:** Métricas basadas en teoría musical (distribución de notas, intervalos, calidad armónica).
- **Generación:** Creación y exportación de nuevas melodías en formato MIDI.

## Requisitos

- Python 3.8+
- Jupyter Notebook
- Paquetes: `pretty_midi`, `music21`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`, `keras`, `torch`, `pypianoroll`, `huggingface_hub`, entre otros.

## Ejemplo de ejecución
Puedes ejecutar el notebook paso a paso en Google Colab usando el siguiente enlace:


<img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg">

## Créditos
- Autor: Santiago Pérez G.
- Basado en técnicas y librerías de procesamiento musical y deep learning.