# Showz_Marketing_Analysis
Optimizar los gastos de marketing - Showz (empresa de venta de entradas de eventos). 

Optimizing Marketing Expenses - Showz (Event Ticket Sales Company).

Proyecto hecho para TripleTen (Bootcamp online) - Sprint 9. Análisis de negocios. 

Project completed for TripleTen (Online Bootcamp) - Sprint 9. Business Analysis.

## Contexto / Context
Este proyecto forma parte de mi aprendizaje en análisis de datos, donde se me asignó la tarea de optimizar los gastos de marketing para Showz, una empresa de venta de entradas de eventos.

El objetivo del análisis es comprender el comportamiento de los clientes, evaluar la rentabilidad de las inversiones en marketing y formular recomendaciones estratégicas basadas en datos.

---

This project is part of my apprenticeship in data analytics, where I was tasked with optimizing marketing spend for Showz, an event ticketing company.

The goal of the analysis is to understand customer behavior, evaluate the return on marketing investments and formulate strategic recommendations based on data.

## Objetivos / Objectives
- Analizar el comportamiento de los clientes en la plataforma (frecuencia de visitas, conversión y compras). 
- Evaluar la rentabilidad de las campañas de marketing mediante métricas clave como CAC (Costo de Adquisición de Clientes) y ROMI (Retorno de Inversión en Marketing). 
- Identificar las fuentes de adquisición más efectivas para optimizar la inversión publicitaria.

---

- Analyze customer behavior on the platform (frequency of visits, conversion and purchases).
- Analyze customer behavior on the platform (frequency of visits, conversion and purchases).
- Identify the most effective acquisition sources to optimize advertising spend.

## Datos Utilizados / Data Used
Se trabajó con tres conjuntos de datos provenientes del servidor de Showz 
- visits_log_us.csv: Registros de visitas. Información sobre sesiones de usuarios, dispositivos y fuentes de tráfico. 
- orders_log_us.csv: Pedidos. Datos de compras, ingresos y comportamiento de conversión. 
- costs_us.csv: Gastos de marketing. Costos de adquisición de clientes según la fuente de anuncios. 

---

Three data sets from the Showz server were used:
- visits_log_us.csv: Visits logs. Information about user sessions, devices and traffic sources.
- orders_log_us.csv: Orders. Purchasing, revenue and conversion behavior data.
- costs_us.csv: Marketing expenses. Customer acquisition costs by ad source.

## Herramientas Utilizadas / Tools Used
- Python: Lenguaje principal para la manipulación y análisis de datos. 
- pandas: Manipulación y limpieza de datos. 
- numpy: Cálculos numéricos y optimización de datos. 
- matplotlib: Visualización de datos para identificar patrones y tendencias. 
- Jupyter Notebook: Organización del análisis en un entorno interactivo. 

---

-  Python: Main language for data manipulation and analysis.
-  pandas: Data manipulation and cleaning.
-  numpy: Numerical calculations and data optimization.
-  matplotlib: Data visualization to identify patterns and trends.
-  Jupyter Notebook: Organizing analysis in an interactive environment.

## Análisis Realizado / Analysis Performed
1. Comportamiento de los Usuarios
  - Cantidad de usuarios por día, semana y mes.
  - Número de sesiones por usuario y duración promedio.
  - Retención y frecuencia de regreso de los usuarios.
2. Análisis de Ventas
  - Tiempo entre el registro y la primera compra (Conversion 0d, 1d, etc.).
  - Número total de pedidos y ticket promedio.
  - Valor del Cliente en el Tiempo (LTV).
3. Evaluación de Marketing
  - Gastos de marketing por fuente y periodo de tiempo.
  - Costo de Adquisición de Clientes (CAC) por fuente.
  - Rentabilidad de las inversiones en marketing (ROMI).

---

1. User Behavior
  - Number of users per day, week and month.
  - Number of sessions per user and average duration.
  - Retention and return frequency of users.
2. Sales Analysis
  - Time between registration and first purchase (Conversion 0d, 1d, etc.).
  - Total number of orders and average ticket.
  - Customer Time to Value (LTV).
3. Marketing Evaluation
  - Marketing expenditures by source and time period.
  - Customer Acquisition Cost (CAC) by source.
  - Return on Marketing Investments (ROMI).
