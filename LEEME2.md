# CFE-IA-E2

# Regresión Lineal Múltiple

## **Características elegidas**
Las características seleccionadas para entrenar el modelo son:
- **Independientes**
  - edad (años del paciente).
  - tiempo (días de seguimiento médico).
- **Dependientes**
  - Muerte (death_event: fallecimiento durante el seguimiento)
  
## **Instrucciones de uso:**
- Colocar el archivo clinica.csv en la misma carpeta del script.
- Verificar que se tengan todas las librerías necesarias instaladas:
  - pip install pandas
  - pip install matplotlib
  - pip install seaborn
  - pip install scikit-learn
- Ejecutar el archivo regresionlinealmultiple.py

## **Para realizar una predicción manual:**
- Modifica los valores de edad y tiempo dentro del código.
- El modelo devolverá la probabilidad estimada de fallecimiento en porcentaje.

## Identificación de umbrales (>70%)

**Identificar valores donde el riesgo supera el 70%.**
- Con una edad de 65 años y un tiempo de 4 días se obtiene un resultado de 72.1%.

**Valores de edad a partir de los cuales la probabilidad de fallecimiento excede el 70%.**
- Con 60 años en adelante, manteniendo fijo el seguimiento en 1 día, las probabilidades de fallecimiento superan el 70%.

**Valores de tiempo de seguimiento (en días) a partir de los cuales el riesgo también supera el 70%.**
- Con una edad fija de 70 años, comenzando desde 20 días de observación y bajando hasta 1 día, todos los casos superan el 70%.

**SALUDOS :)**
