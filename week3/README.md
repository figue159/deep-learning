
# Red Neuronal Básica – Comparación de Activaciones

## Objetivo
Implementar una red neuronal simple para el problema lógico OR y comparar el desempeño de distintas funciones de activación.

## Implementación
- Red neuronal con una capa oculta entrenable mediante backpropagation.  
- Se registró la evolución del loss durante las épocas y se calculó la métrica de accuracy.  
- Se generaron gráficos para visualizar el proceso de entrenamiento.

## Activaciones comparadas
- **Sigmoid**  
- **ReLU**

## Resultados principales
- Con Sigmoid: Loss final ≈ 0.18, Accuracy = 0.75  
- Con ReLU: Loss final ≈ 0.066, Accuracy = 1.0  
- ReLU mostró un aprendizaje más rápido y preciso.

## Ejecución del notebook
1. Abrir el archivo `notebook.ipynb` en Google Colab o Jupyter Notebook.  
2. Ejecutar todas las celdas en orden.  
3. Al final se mostrarán los gráficos de pérdida y las métricas de evaluación.
