# Modelo Econométrico para la Predicción de Obesidad

Este proyecto presenta un modelo econométrico diseñado para estimar el grado de obesidad en función de variables relacionadas con características individuales y hábitos de vida. Este modelo tiene como objetivo principal identificar los factores más relevantes que influyen en la obesidad, proporcionando una herramienta útil para la creación de estrategias de intervención y políticas públicas.

## Variables Incluidas

### Variable Dependiente
- *Peso (Weight):* Representa el grado de obesidad.

### Variables Independientes
1. *Edad (Age):* Edad en años.
2. *Altura (Height):* Altura en metros.
3. *Antecedentes Familiares (Family History with Overweight):* Presencia de sobrepeso en familiares.
4. *Consumo de Alimentos Calóricos (FAVC):* Frecuencia de ingesta de alimentos altos en calorías.
5. *Consumo de Vegetales (FCVC):* Frecuencia de consumo de vegetales.
6. *Número de Comidas Principales (NCP):* Cantidad de comidas principales diarias.
7. *Consumo entre Comidas (CAEC):* Consumo de alimentos entre comidas.
8. *Consumo de Agua (CH2O):* Litros de agua consumidos al día.
9. *Actividad Física (FAF):* Frecuencia de actividad física semanal.
10. *Uso de Tecnología (TUE):* Tiempo dedicado a dispositivos electrónicos.
11. *Consumo de Alcohol (CALC):* Frecuencia de consumo de bebidas alcohólicas.
12. *Medio de Transporte (MTRANS):* Modo de transporte utilizado regularmente.

## Metodología

1. *Construcción del Modelo:*
   - Se utilizó un modelo de regresión lineal múltiple para evaluar las relaciones entre el peso y las variables independientes.
   - Los parámetros fueron estimados mediante el método de Mínimos Cuadrados Ordinarios (MCO).
   
2. *Problemas Identificados y Soluciones:*
   - *Multicolinealidad:* Detectada en algunas variables, fue tratada manteniendo aquellas con mayor importancia predictiva y explorando técnicas de regularización.
   - *Heterocedasticidad:* Corregida mediante Mínimos Cuadrados Ponderados (MCP), mejorando la consistencia de los estimadores.

3. *Evaluación del Modelo:*
   - Coeficientes de determinación \(R^2\) y \(R^2_{ajustado}\) mostraron un ajuste razonable (57.6% de varianza explicada).
   - Criterios de información (AIC y BIC) fueron utilizados para comparar y optimizar el modelo.

## Resultados

El modelo identificó los factores clave que afectan el peso, como:
- Altura, edad y antecedentes familiares de sobrepeso con un impacto positivo.
- Actividad física y uso de tecnología asociados a una disminución del peso.

## Conclusión

Este modelo econométrico proporciona una base sólida para el análisis de la obesidad, identificando variables críticas que pueden guiar intervenciones efectivas. A pesar de sus limitaciones, representa un paso importante hacia una comprensión más integral del problema.

## Recursos

- [Dataset de Kaggle](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels)
- Código y materiales disponibles en [este repositorio](https://github.com/ElblogdeIsmael/ElblogdeIsmael.github.io/tree/main/Asignaturas/Tercer%20A%C3%B1o/ECO/Practicas/Trabajo).
