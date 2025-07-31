# Machine Learning 

Este repositorio contiene la práctica del módulo de **Machine Learning*. 
El objetivo es aplicar técnicas supervisadas de clasificación binaria para predecir cancelaciones de reservas en un hotel a partir del conjunto de datos del CSV que nos han entregado.

---

## Objetivos

Desarrollar y evaluar modelos de clasificación binaria que permitan predecir si una reserva será cancelada (`is_canceled`) en función de múltiples variables de entrada.  
Usaremos **accuracy**, **F1-score** y **AUC-ROC** com métricas para comparar el rendimiento de cada modelo.

---

## Modelos entrenados

Se han entrenado y comparado los siguientes algoritmos:

- Regresión Logística
- Árbol de Decisión
- Random Forest
- Gradient Boosting (XGBoost)

---

## Repositorio

```
.
├── data/
│   └── dataset_practica_final.csv   # Dataset original en formato CSV
├── evaluacion_final.ipynb           # Notebook completo que hemos hecho Sergi i Jordi
├── evaluacion_final.html            # Versión HTML del notebook (exportado)
├── README.md                        # Este archivo
└── requirements.txt                 # Este archivo
```

---

## Visualización rápida

Si no deseas ejecutar el notebook, puedes ver el informe completo en formato HTML directamente desde [evaluacion_final.html](./evaluacion_final.html) o abrirlo con cualquier navegador.

---

## Requisitos técnicos

Instalación con `pip`:

```bash
pip install -r requirements.txt
```

---

## Autores

- **Sergi Justiniano** & **Jordi Nadal**  
- Proyecto final – Módulo Machine Learning  
- Máster Pontia.tech en Inteligencia Artificial (2025)

