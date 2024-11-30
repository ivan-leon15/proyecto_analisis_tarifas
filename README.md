# Proyecto: Análisis de Tarifas de Prepago en Megaline  

## Contexto  
Megaline, un operador de telecomunicaciones, ofrece dos tarifas de prepago: **Surf** y **Ultimate**. El objetivo principal de este proyecto es analizar cuál de estas tarifas genera mayores ingresos, proporcionando datos esenciales para que el departamento comercial pueda optimizar su presupuesto publicitario. El análisis se basa en datos recopilados de 500 clientes durante 2018, los cuales incluyen detalles sobre llamadas, mensajes de texto y uso de internet.  

## Herramientas Utilizadas  
- **Python:** Para la limpieza, exploración y análisis de datos.  
- **Pandas:** Manejo y manipulación de grandes volúmenes de datos.  
- **NumPy:** Operaciones matemáticas y estadística.  
- **Matplotlib y Seaborn:** Visualización gráfica de los resultados.  
- **Scipy.stats:** Realización de pruebas estadísticas como la prueba t y ANOVA.  

## Análisis de Resultados  
### 1. **Exploración Inicial**  
- Se analizaron las cinco tablas disponibles:  
  1. **users:** Información general de los clientes.  
  2. **calls:** Detalles sobre las llamadas realizadas.  
  3. **messages:** Registro de los mensajes enviados.  
  4. **internet:** Sesiones de uso de datos.  
  5. **plans:** Descripción de las tarifas disponibles.  

- Se realizó una verificación inicial de los datos para identificar valores ausentes, duplicados y posibles inconsistencias en los formatos.  

### 2. **Limpieza de Datos**  
- Los valores nulos se manejaron mediante imputación o eliminación según el contexto.  
- Se eliminaron duplicados y se estandarizaron las unidades de medida.  
- El uso de minutos y datos se redondeó según las reglas de cobro de Megaline: minutos y gigabytes se aproximan al entero más cercano.  

### 3. **Comportamiento del Cliente**  
- Se identificaron patrones en el uso de minutos, mensajes y datos.  
  - Los clientes de **Surf** tienden a superar con frecuencia los límites incluidos en su plan.  
  - Los clientes de **Ultimate**, debido a su capacidad ampliada, no suelen generar cargos adicionales.  
- Se evaluaron ingresos promedio por cliente en ambos planes, incluyendo pagos mensuales y costos por excedentes.  

### 4. **Pruebas Estadísticas**  
- Se realizó una comparación de los ingresos promedio utilizando una prueba t de dos muestras para verificar diferencias significativas.  
- Se complementó con un análisis ANOVA para evaluar las variaciones en ingresos entre subgrupos de usuarios con diferentes comportamientos.  
- Los resultados mostraron que, aunque **Ultimate** tiene un mayor costo fijo, **Surf** genera ingresos significativos a través de cargos adicionales.  

## Conclusiones  
El análisis reveló que el plan **Surf** genera mayores ingresos promedio por cliente debido a los cargos adicionales aplicados por excedentes. Esto sugiere que el departamento de marketing debería considerar las siguientes recomendaciones:  
- Enfocar campañas publicitarias en destacar el plan **Surf**, especialmente para clientes con patrones de uso intensivo.  
- Reevaluar las tarifas y límites incluidos en **Ultimate** para hacerlo más competitivo.  
- Optimizar la estrategia de retención de clientes para ambos planes, destacando los beneficios específicos que ofrecen.  

Estas conclusiones proporcionan una base sólida para la toma de decisiones estratégicas que maximizan la rentabilidad y mejoran la experiencia del cliente.  
