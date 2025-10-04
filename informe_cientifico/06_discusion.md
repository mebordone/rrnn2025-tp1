## Discusión

Los resultados obtenidos confirman la capacidad del modelo de Izhikevich para reproducir los diferentes tipos de disparo neuronal documentados experimentalmente. Las simulaciones muestran una correspondencia cualitativa excelente con los patrones observados en neuronas reales:

1. **Neuronas RS**: La adaptación de frecuencia se reproduce correctamente mediante la combinación de parámetros c=-65 mV y d=8, que generan un reseteo profundo y un salto grande en la variable de recuperación.

2. **Neuronas IB**: El bursting inicial seguido de disparos regulares se logra con c=-55 mV y d=4, permitiendo que la variable u se acumule durante el burst inicial.

3. **Neuronas CH**: Los bursts de alta frecuencia se obtienen con c=-50 mV y d=2, resultando en un reseteo muy alto que facilita el disparo rápido.

4. **Neuronas FS**: La alta frecuencia sin adaptación se consigue con a=0.1, que acelera la recuperación de la variable u.

Las posibles fuentes de error numérico incluyen la discretización temporal (paso h=0.1 ms) y las aproximaciones del método RK4, aunque estos errores son despreciables para los propósitos de este estudio.

El modelo de Izhikevich demuestra ser una herramienta invaluable para el estudio de dinámicas neuronales, ofreciendo un balance óptimo entre realismo biológico y eficiencia computacional. Su capacidad para reproducir múltiples tipos de disparo con solo cuatro parámetros lo convierte en un modelo canónico para simulaciones de redes neuronales a gran escala.
