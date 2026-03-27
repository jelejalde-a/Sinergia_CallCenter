# Sinergia Call S.A.S  

Sinergia Call Center es un proyecto de análisis de datos que optimiza la gestión de un call center mediante BI. Integra, transforma y visualiza datos de clientes, llamadas y casos, permitiendo medir KPIs, identificar patrones y apoyar la toma de decisiones con dashboards en Power BI.

---

## Descripción 

Se realizó una simulación de datos reales de un call center, se tuvieron en cuenta datos de Departamentos, agentes, clientes, servicios tercerizados, llamadas, facturas y mas, para un total de 13 tablas que permiten realizar una visualización de una eficiencia operativa y un manejo de agentes y servicios ofrecidos. La arquitectura de datos propuesta conecta el desempeño de los departamentos y de sus agentes, con la satisfacción de los clientes y el recaudo financiero de la compañía. Esto permite identificar los puntos críticos en la atención y las oportunidades de crecimiento y mejoras en la forma de analizar y mostrar los datos de manera mas efectiva.

---

## Stack Tecnológico  

- **Draw.io**: Realización del modelo relacional  
- **Visual Studio Code (Python)**:  
  - Librería `Faker` para simulación de datos con localización colombiana  
  - Procesamiento y limpieza de datasets operativos  
- **SQL**: Visualización y consultas iniciales a la base de datos para calidad y lógica del negocio  
- **Power BI**:  
  - Visualización avanzada de resultados  
  - Desarrollo de consultas DAX  
  - KPIs y métricas clave  
  - Tableros de control  

---

## Dashboards  

### Tablero #1  
Parámetros generales de operación del callcenter, análisis de casos, agentes y llamadas.
### Tablero #2  
Panel de clientes, segmentación por perfil, análisis de retención; monitoreo de calidad (satisfacción y efectividad), gestión de cartera (facturado vs recaudado) y análisis de riesgo (churn).  

---

## Hallazgos principales  

- 55% de casos resueltos, con el 49% resuelto en la primera llamada, para un SLA cumplido en el 66% de los casos (resueltos en el tiempo estipulado).  
- Duración promedio de llamada de 5,73 min, con el 70% de llamadas atendidas efectivamente y, de estas, el 93% atendidas en menos de 2 min. Además, hay una ocupación real del 64% de los agentes.  
- Se observó sobrecarga de trabajo en los agentes de soporte técnico, que acumulan la mayoría de los casos.  
- Media satisfacción de los clientes (3.8) y eficiencia sobre llamadas entrantes (70%), lo que indica una necesidad de mejora en la atención.  
- Necesidad de acciones preventivas sobre el riesgo de churn, ya que el riesgo alto y medio suma más del 50%.  
- La mayoría de los clientes se encuentra en el rango de 46 a 60 años, siendo este un segmento que valora la estabilidad y el soporte técnico atendido por humanos.  

---

## Recomendaciones  

- Hacer campañas segmentadas por clientes identificados según riesgo de churn.  
- Distribuir estratégicamente el número de agentes en cada departamento según la demanda de casos.  

**Oportunidades de mejora:**  
Implementar Databricks para procesar la información contenida en el historial de 4 años de operación de Sinergia.  

---

## Dashboard Power BI  

[Ver dashboard interactivo](https://app.powerbi.com/view?r=eyJrIjoiZmI1ZWY4OGQtNGU5Ny00MjNhLWE0MDMtNzFkYjdlZWJhN2UwIiwidCI6IjU3N2ZjMWQ4LTA5MjItNDU4ZS04N2JmLWVjNGY0NTVlYjYwMCIsImMiOjR9)

---

## Equipo  

- Juliana Elejalde Garcia  
- Zuleima Beatriz Carriazo  
- Leidy Tatiana Sabogal Ardila  

Proyecto realizado durante el Bootcamp de Análisis de Datos con Betek y Makaia, cohorte 13.  
Noviembre 2025 – Marzo 2026  
