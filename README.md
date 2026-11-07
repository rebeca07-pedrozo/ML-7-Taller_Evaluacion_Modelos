# Taller: Evaluación de modelos y ajuste de hiperparámetros

Machine Learning – Universidad Libre
Rebeca Pedrozo Cueto

Cuaderno: **`Taller_Evaluacion_Modelos.ipynb`** (ya ejecutado, con todas las salidas).

## Pasos del taller

1. Cargar datos y dividir en entrenamiento y prueba
2. Medir MAE, RMSE y R² en entrenamiento vs. prueba
3. Detectar el sobreajuste: polinomios de grado 1 a 15
4. Validación cruzada: comparar 3 modelos
5. `GridSearchCV` y `RandomizedSearchCV`
6. Clasificación: matriz de confusión, F1 y AUC

## Datos

Se usan datasets incluidos en scikit-learn, así que no hay que subir archivos:

- **Regresión** (pasos 1–5): `load_diabetes`
- **Clasificación** (paso 6): `load_breast_cancer`

## Cómo ejecutarlo

En Google Colab: subir el `.ipynb` y ejecutar las celdas en orden.

En local:

```bash
pip install scikit-learn pandas matplotlib jupyter
jupyter notebook Taller_Evaluacion_Modelos.ipynb
```
