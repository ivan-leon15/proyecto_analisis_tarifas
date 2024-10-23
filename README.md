# Proyecto: Análisis de Tarifas de Prepago en Megaline

## Descripción General
Trabajas como analista para **Megaline**, un operador de telecomunicaciones que ofrece dos tarifas de prepago: **Surf** y **Ultimate**. El objetivo de este proyecto es **determinar cuál de los dos planes genera más ingresos**, ayudando al departamento comercial a ajustar su presupuesto de publicidad. Se trabajará con un conjunto de datos de **500 clientes** que incluye información sobre sus llamadas, mensajes y uso de internet en 2018.

## Objetivo del Proyecto
El análisis se centrará en el comportamiento de los clientes en función de la tarifa que utilizan y se realizarán **pruebas estadísticas** para determinar qué plan, en promedio, aporta más ingresos a la empresa. El resultado permitirá **optimizar la estrategia comercial** de Megaline.

## Descripción de las Tarifas:

### 1. **Surf**:
- Pago mensual: **20$**.
- Incluye: **500 minutos**, **50 SMS** y **15 GB de datos**.
- Costos adicionales:
  - 1 minuto extra: **3 centavos**.
  - 1 SMS extra: **3 centavos**.
  - 1 GB extra: **10$**.

### 2. **Ultimate**:
- Pago mensual: **70$**.
- Incluye: **3000 minutos**, **1000 SMS** y **30 GB de datos**.
- Costos adicionales:
  - 1 minuto extra: **1 centavo**.
  - 1 SMS extra: **1 centavo**.
  - 1 GB extra: **7$**.

### Notas sobre el Cobro:
- Las llamadas se redondean al minuto más cercano.
- El uso de internet se redondea al gigabyte más cercano al final del mes.

## Diccionario de Datos
El análisis utiliza cinco tablas distintas que contienen información sobre los clientes, sus llamadas, mensajes, sesiones web y las tarifas. 

### 1. **users** (Datos sobre los usuarios):

### 2. **calls** (Datos sobre las llamadas):

### 3. **messages** (Datos sobre los SMS):

### 4. **internet** (Datos sobre las sesiones web):

### 5. **plans** (Datos sobre las tarifas):

## Contenido del Proyecto:
- **Carga y previsualización de datos**: Verificación de la estructura y contenido del conjunto de datos.
- **Limpieza de datos**: Manejo de valores ausentes y duplicados.
- **Análisis exploratorio**: Estudio del comportamiento de los clientes según su tarifa y uso.
- **Pruebas estadísticas**: Comparación de los ingresos generados por las tarifas mediante técnicas estadísticas.
- **Conclusiones**: Determinación del plan más rentable en términos de ingresos generados.

## Conclusión:
El análisis permitirá a **Megaline** tomar decisiones informadas sobre cuál tarifa genera más ingresos, optimizando así su estrategia de marketing y presupuesto de publicidad.
