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

**SALUDOS :)**
