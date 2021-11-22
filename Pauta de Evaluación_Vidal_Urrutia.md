# Pauta de Evaluación

| Item | Puntaje Ideal | Puntaje Real| Observaciones generales |
|------|---------------|-------------|-------------------------|
|Punto Base | 1 | 1 | |
| README | 0.5 | 0.5 | Bien |
| Commits | 0.5 | 0.5 | Bien |
| Ejercicio 1 - Teoría | 0.5 | 0.5 | Ordenado |
| Ejercicio 1 - Practico | 0.75 | 0.75 | Prolijo |
| Ejercicio 2 - Teoria | 1.25 | 1.25 | Buen uso de lenguaje matemático|
| Ejercicio 2 - Practico | 1.5 | 1.4 |Error en la implementacion de RMS |
| Ejercicio 3 - Teorico | 1 | 1 | Correcto razonamiento en el uso de normalizaciones|
| **Total** | 7 | 6.9 | ||

+ Buen trabajo realizado. El orden en los codigos y el uso de lenguaje matemático.
+ Cuidado al interpretar ecuaciones matemáticas en lenguaje de programación, la normalizacion RMS posee dentro de la raiz cuadrada el siguiente denominador:
\begin{equation}
\sum_{i=1}^{N}x(i)^2
\end{equation}
lo que en python, utilizando numpy se traduce de la siguiente manera:
```python
np.sum(sig**2)
```
+ Este error se ve reflejado en el grafico correspondiente a esta normalización. Sin embargo ustedes no se percatan de esto, ya que el eje Y tiene una escala de $1*10^6$ lo cual llama inmediatamente la atención.
+ Felicitaciones por el grado de dedicación y de análisis. 