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

Las figuras referenciadas en el informe se encuentran en la carpeta `../images/`:
- `izhikevich_simulacion_completa.png`
- `potencial_membrana_vs_tiempo.png`
- `variable_recuperacion_vs_tiempo.png`
- `espacio_fases_v_vs_u.png`
- `corriente_entrada_vs_tiempo.png`
- `todas_las_neuronas_combinadas.png`
- `neurona_RS_Regular_Spiking.png`
- `neurona_IB_Intrinsically_Bursting.png`
- `neurona_CH_Chattering.png`
- `neurona_FS_Fast_Spiking.png`
- `neurona_TC1_Thalamo_Cortical_1.png`
- `neurona_TC2_Thalamo_Cortical_2.png`
- `neurona_RZ_Resonator.png`
- `neurona_LTS_Low_Threshold_Spiking.png`
