## Resultados

### Simulación básica del modelo

La simulación inicial del modelo con parámetros estándar muestra la evolución temporal del potencial de membrana y la variable de recuperación. Se observa que el sistema evoluciona hacia un estado estable sin disparos, lo cual es consistente con la ausencia de corriente de entrada en los primeros 10 ms de simulación.

![Simulación completa del modelo de Izhikevich](../images/izhikevich_simulacion_completa.png)
*Figura 1: Simulación completa del modelo de Izhikevich mostrando la evolución temporal del potencial de membrana v(t), la variable de recuperación u(t), el espacio de fases (v vs u) y la corriente de entrada I(t).*

![Evolución temporal del potencial de membrana](../images/potencial_membrana_vs_tiempo.png)
*Figura 2: Evolución temporal del potencial de membrana v(t) para parámetros estándar del modelo.*

![Evolución temporal de la variable de recuperación](../images/variable_recuperacion_vs_tiempo.png)
*Figura 3: Evolución temporal de la variable de recuperación u(t) que modela la activación de corrientes K+ y la inactivación de corrientes Na+.*

![Espacio de fases](../images/espacio_fases_v_vs_u.png)
*Figura 4: Espacio de fases (v vs u) mostrando la trayectoria del sistema en el plano de estado. El punto verde indica el estado inicial y el punto rojo el estado final.*

![Corriente de entrada](../images/corriente_entrada_vs_tiempo.png)
*Figura 5: Corriente de entrada I(t) aplicada al modelo. Se observa que la corriente se activa en t=10 ms con un valor de 10 unidades.*

### Reproducción de tipos neuronales

Se implementaron simulaciones para ocho tipos neuronales distintos según la parametrización del paper original de Izhikevich:

![Vista combinada de todos los tipos neuronales](../images/todas_las_neuronas_combinadas.png)
*Figura 6: Vista combinada de los ocho tipos neuronales simulados. Cada panel muestra la evolución temporal del potencial de membrana para diferentes parametrizaciones del modelo.*

**Neuronas excitatorias corticales:**

![Neurona Regular Spiking](../images/neurona_RS_Regular_Spiking.png)
*Figura 7: Neurona RS (Regular Spiking) mostrando adaptación de frecuencia característica. Los intervalos entre spikes aumentan gradualmente.*

![Neurona Intrinsically Bursting](../images/neurona_IB_Intrinsically_Bursting.png)
*Figura 8: Neurona IB (Intrinsically Bursting) exhibiendo bursting inicial seguido de disparos regulares.*

![Neurona Chattering](../images/neurona_CH_Chattering.png)
*Figura 9: Neurona CH (Chattering) presentando bursts de spikes muy cercanos temporalmente con alta frecuencia.*

**Neuronas inhibitorias corticales:**

![Neurona Fast Spiking](../images/neurona_FS_Fast_Spiking.png)
*Figura 10: Neurona FS (Fast Spiking) disparando a alta frecuencia sin adaptación significativa.*

![Neurona Low Threshold Spiking](../images/neurona_LTS_Low_Threshold_Spiking.png)
*Figura 11: Neurona LTS (Low Threshold Spiking) con alta frecuencia y adaptación moderada.*

**Neuronas talamocorticales:**

![Neurona Thalamo-Cortical 1](../images/neurona_TC1_Thalamo_Cortical_1.png)
*Figura 12: Neurona TC1 mostrando respuesta tónica a corriente constante.*

![Neurona Thalamo-Cortical 2](../images/neurona_TC2_Thalamo_Cortical_2.png)
*Figura 13: Neurona TC2 exhibiendo respuesta de rebote tras hiperpolarización.*

**Neuronas resonadoras:**

![Neurona Resonator](../images/neurona_RZ_Resonator.png)
*Figura 14: Neurona RZ (Resonator) con oscilaciones subumbrales y comportamiento resonante.*
