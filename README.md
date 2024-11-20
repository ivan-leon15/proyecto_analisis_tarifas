# Análisis de Eficiencia de Operadores en Servicio Telefónico Virtual  

## Contexto  
Este proyecto busca evaluar el desempeño de operadores en un servicio de telefonía virtual mediante el análisis de métricas clave como:  
- Total de llamadas realizadas y recibidas.  
- Duración promedio de las llamadas.  
- Número de llamadas perdidas.  
- Tiempo promedio de espera.  
- Clasificación de llamadas en entrantes y salientes.  

El análisis tiene como objetivo optimizar la eficiencia operativa y mejorar la calidad del servicio ofrecido.  

## Herramientas Utilizadas  

### Lenguaje de Programación  
- **Python**  

### Bibliotecas de Python  
- **pandas**: Manipulación y análisis de datos.  
- **matplotlib** y **seaborn**: Creación de visualizaciones.  
- **scikit-learn**: Construcción y evaluación de modelos predictivos.  
- **scipy**: Pruebas estadísticas y validación de hipótesis.  

### Software de Visualización  
- **Tableau**: Generación de visualizaciones avanzadas para análisis y presentación de resultados.  
- **Jupyter Notebook**: Ejecución del código y documentación interactiva del proyecto.  

## Análisis de Resultados  

### Transformación de Datos  
Se realizaron los siguientes procesos:  
1. **Estandarización y normalización** de variables relevantes para garantizar uniformidad en el análisis.  
2. **Categorización de operadores** en "eficientes" e "ineficientes" con base en:  
   - Número de llamadas perdidas.  
   - Tiempo de espera en llamadas entrantes.  
   - Número de llamadas salientes realizadas.  

### Análisis Exploratorio de Datos  
- Gráficos como histogramas, diagramas de dispersión y gráficos de barras ayudaron a identificar patrones y tendencias clave.  
- Mapas de calor revelaron correlaciones entre variables como duración promedio y llamadas perdidas.  

### Prueba A/B  
Se realizó una prueba t de dos muestras para comparar operadores clasificados como "eficientes" e "ineficientes" en términos de llamadas perdidas.  

### Modelado de Datos  
- Se entrenaron modelos de **regresión logística** y **árboles de decisión** para predecir la eficiencia de los operadores.  
- Las métricas de evaluación incluyeron precisión, recall y accuracy para determinar el rendimiento de los modelos.  

## Conclusiones  

### Resultados  
1. **Prueba A/B**: Se confirmó una diferencia significativa en el número de llamadas perdidas entre operadores eficientes e ineficientes, validando la hipótesis inicial.  
2. **Modelos Predictivos**: La regresión logística demostró ser particularmente efectiva para clasificar operadores, mientras que los árboles de decisión facilitaron interpretaciones más claras.  

### Impacto y Recomendaciones  
- Se identificaron áreas críticas para intervención, como la capacitación de operadores con bajo rendimiento.  
- Se sugirió implementar alertas tempranas basadas en modelos predictivos para mitigar problemas de eficiencia.  

## Visualización  
Las visualizaciones generadas en Python y Tableau proporcionaron información clave para comunicar los hallazgos a las partes interesadas, incluyendo:  
- Comparaciones gráficas de llamadas perdidas.  
- Diagramas que resaltan las diferencias en tiempo de espera y llamadas salientes.  
- Mapas de calor que muestran correlaciones entre métricas críticas.  

## Conclusión General  
Este proyecto demostró cómo el análisis de datos puede ser una herramienta poderosa para mejorar la eficiencia operativa en servicios de telefonía virtual. Los resultados no solo validaron la hipótesis inicial, sino que también ofrecieron una guía clara para la implementación de mejoras estratégicas.  
