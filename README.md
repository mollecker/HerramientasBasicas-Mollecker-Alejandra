# Análisis Exploratorio de Datos - Cuba 7076

Proyecto de análisis exploratorio de datos (EDA) para el monitoreo de variables operativas e industriales en la cuba de producción C7076 durante un período de 3 meses.

## Descripción del Proyecto

Este proyecto contiene un flujo de trabajo en Python desarrollado para procesar y analizar mediciones temporales de la cuba 7076. El dataset abarca 179 variables operativas (temperatura, tensión, energía, insumos químicos, etc.) registradas por turnos y semi-turnos.

Objetivos principales:
- Carga y limpieza: Lectura adecuada del archivo CSV con delimitador de punto y coma ';'.
- Exploración de dimensiones y tipos de datos: Inspección inicial del volumen de datos (729 registros) y sus tipos de datos.
- Estadística descriptiva: Análisis de promedios, desviaciones estándar, mínimos y máximos de variables críticas.
- Visualización de datos: Análisis de distribución de variables clave (como la temperatura TFE).

## Requisitos e Instalación

Para ejecutar este cuaderno se requieren las siguientes librerías de Python:

pip install pandas matplotlib seaborn plotly

## Estructura del Dataset (Practica C7076.csv)

- Registros (Filas): 729 entradas correspondientes a semi-turnos operativos.
- Variables (Columnas): 179 columnas con información técnica, entre las que destacan:
  * FT_TURNO / TU_SEMI_TURNO: Identificadores temporales y de turno.
  * CUBA: Identificador del equipo (7076).
  * TFE: Temperatura registrada.
  * V_ULT_V, V_ULT_TI, V_ULT_GA: Variables operativas de voltaje, tiempo y gas.
  * Insumos y aditivos (ALF3, AMCRY, etc.).
