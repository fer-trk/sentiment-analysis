# Entrenamiento y evaluación reproducibles

## Criterios de aceptación

- [x] Verificar que el CSV y el manifiesto cubren las filas esperadas y que las particiones no comparten vídeos ni textos normalizados.
- [x] Acordar Logistic Regression + TF-IDF para `IsToxic`, F1 de la clase positiva y un objetivo de recall del 80 % en validación.
- [x] Reproducir la línea base y aplicar el mismo umbral en entrenamiento, validación y test histórico.
- [x] Documentar la brecha y si cumple el objetivo de menos de 5 puntos porcentuales.

El [informe de la línea base](../model/logistic-tfidf.md#reproducción-del-test-histórico)
contiene el comando, las versiones, los resultados y las limitaciones.
La búsqueda de hiperparámetros corresponde al PR #6.
