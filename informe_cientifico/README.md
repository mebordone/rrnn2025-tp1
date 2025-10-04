# Informe Científico - Modelo de Izhikevich

## Estructura del informe

Este directorio contiene el informe científico dividido en secciones independientes para facilitar la edición:

- `01_titulo_autores.md` - Título y datos de autores
- `02_resumen.md` - Resumen/Abstract del trabajo
- `03_introduccion.md` - Introducción y contexto
- `04_teoria.md` - Marco teórico y ecuaciones del modelo
- `05_resultados.md` - Resultados y análisis de simulaciones
- `06_discusion.md` - Discusión de resultados
- `07_referencias.md` - Referencias bibliográficas

## Cómo compilar el informe completo

Para generar el informe completo, puedes usar uno de estos métodos:

### Método 1: Usando cat (Linux/Mac)
```bash
cat 01_titulo_autores.md 02_resumen.md 03_introduccion.md 04_teoria.md 05_resultados.md 06_discusion.md 07_referencias.md > informe_completo.md
```

### Método 2: Usando pandoc
```bash
pandoc 01_titulo_autores.md 02_resumen.md 03_introduccion.md 04_teoria.md 05_resultados.md 06_discusion.md 07_referencias.md -o informe_completo.pdf
```

### Método 3: Manual
Copia y pega el contenido de cada archivo en orden en un nuevo documento.

## Instrucciones de edición

1. **Completa tus datos personales** en `01_titulo_autores.md`
2. **Ajusta las referencias a figuras** en `05_resultados.md` con los nombres exactos de los archivos en la carpeta `images/`
3. **Personaliza el análisis** en `06_discusion.md` según tus observaciones específicas
4. **Revisa y expande** cualquier sección según sea necesario

## Archivos de figuras

Las figuras referenciadas en el informe se encuentran en la carpeta `../images/` y están organizadas de la siguiente manera:

### Simulación básica del modelo (Figuras 1-5):
- `izhikevich_simulacion_completa.png` - Vista completa con 4 subplots
- `potencial_membrana_vs_tiempo.png` - Evolución temporal del potencial
- `variable_recuperacion_vs_tiempo.png` - Evolución temporal de la variable u
- `espacio_fases_v_vs_u.png` - Espacio de fases
- `corriente_entrada_vs_tiempo.png` - Corriente de entrada aplicada

### Tipos neuronales (Figuras 6-14):
- `todas_las_neuronas_combinadas.png` - Vista combinada de los 8 tipos
- `neurona_RS_Regular_Spiking.png` - Regular Spiking
- `neurona_IB_Intrinsically_Bursting.png` - Intrinsically Bursting
- `neurona_CH_Chattering.png` - Chattering
- `neurona_FS_Fast_Spiking.png` - Fast Spiking
- `neurona_LTS_Low_Threshold_Spiking.png` - Low Threshold Spiking
- `neurona_TC1_Thalamo_Cortical_1.png` - Thalamo-Cortical 1
- `neurona_TC2_Thalamo_Cortical_2.png` - Thalamo-Cortical 2
- `neurona_RZ_Resonator.png` - Resonator

### Nota sobre las figuras:
Todas las figuras están referenciadas correctamente en el archivo `05_resultados.md` con descripciones detalladas y numeración secuencial.
