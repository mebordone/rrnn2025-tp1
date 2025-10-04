## Resultados

### Simulación básica del modelo

La simulación inicial del modelo con parámetros estándar muestra la evolución temporal del potencial de membrana y la variable de recuperación (Figura 1). Se observa que el sistema evoluciona hacia un estado estable sin disparos, lo cual es consistente con la ausencia de corriente de entrada en los primeros 10 ms de simulación.

### Reproducción de tipos neuronales

Se implementaron simulaciones para ocho tipos neuronales distintos según la parametrización del paper original de Izhikevich:

**Neuronas excitatorias corticales:**
- **RS (Regular Spiking)**: Muestra adaptación de frecuencia característica (Figura 2a)
- **IB (Intrinsically Bursting)**: Exhibe bursting inicial seguido de disparos regulares (Figura 2b)
- **CH (Chattering)**: Presenta bursts de spikes muy cercanos temporalmente (Figura 2c)

**Neuronas inhibitorias corticales:**
- **FS (Fast Spiking)**: Dispara a alta frecuencia sin adaptación significativa (Figura 2d)
- **LTS (Low Threshold Spiking)**: Alta frecuencia con adaptación moderada (Figura 2e)

**Neuronas talamocorticales:**
- **TC1**: Respuesta tónica a corriente constante (Figura 2f)
- **TC2**: Respuesta de rebote tras hiperpolarización (Figura 2g)

**Neuronas resonadoras:**
- **RZ (Resonator)**: Oscilaciones subumbrales y resonancia (Figura 2h)

La Figura 3 presenta una vista combinada de todos los tipos neuronales, permitiendo comparar directamente sus patrones de disparo característicos.
