# 📊 Dashboard de Gestión de Vacantes | Power BI

## 📌 Descripción del proyecto

Dashboard desarrollado en Power BI para el seguimiento y análisis de requerimientos de personal y gestión de vacantes.

El proyecto permite visualizar el estado de los requerimientos, analizar la cobertura de posiciones y facilitar el seguimiento de indicadores relacionados con los procesos de atracción de talento.

## 🎯 Objetivo

Centralizar y visualizar información de los requerimientos de personal para facilitar el seguimiento de las vacantes, identificar necesidades de cobertura y apoyar la toma de decisiones mediante indicadores y visualizaciones interactivas.

## 🛠️ Herramientas utilizadas

- **Power BI** – Visualización y análisis de datos
- **Power Query** – Limpieza y transformación de datos
- **DAX** – Creación de medidas e indicadores
- **Excel** – Fuente y gestión de datos

## 📊 Principales KPIs y análisis

El dashboard permite analizar los requerimientos de personal desde diferentes perspectivas, facilitando el seguimiento de vacantes, la identificación de oportunidades de cobertura y el análisis de los principales factores que impactan en la gestión de los requerimientos.

### Indicadores de cobertura y disponibilidad

- **% de cobertura de vacantes:** mide la proporción de vacantes en curso que podrían ser cubiertas mediante colaboradores disponibles, considerando la correspondencia entre conocimientos, perfil y requerimientos de la vacante.
- **Disponibilidad de colaboradores:** permite identificar colaboradores disponibles que podrían calzar con los perfiles requeridos.
- **Disponibilidad vs. demanda:** facilita la identificación de oportunidades de asignación y posibles brechas de cobertura.

### Análisis de requerimientos

- **Top de vacantes con mayor cantidad de requerimientos en curso:** permite identificar los perfiles con mayor demanda y analizar posibles causas de concentración.
- **Top de clientes con mayor cantidad de RQ en curso:** identifica los clientes que concentran mayor demanda de personal.
- **Nivel de perfil solicitado:** permite analizar la distribución de los requerimientos según el nivel de experiencia o seniority.
- **Mes con mayor cantidad de solicitudes vigentes:** permite identificar los periodos con mayor volumen de requerimientos.

### Análisis de complejidad y tiempos

- **Perfiles con mayor SLA y demora de cobertura:** permite identificar perfiles complejos o de difícil cobertura y analizar aquellos requerimientos que presentan mayores tiempos de atención.

### Análisis económico

- **% de tasa del colaborador vs. salario:** permite analizar la relación entre la tasa asociada al colaborador y el salario, ayudando a identificar situaciones en las que el costo del recurso puede influir en la decisión del cliente de asumir el costo o descartar la propuesta.

## 🔎 Funcionalidades

El dashboard cuenta con filtros interactivos que permiten segmentar la información por:

- Requerimiento
- Cliente
- Mes
- Año
- Tipo de requerimiento
- Nivel de perfil / seniority
- Coordinador

## 🔎 Principales insights

- Se identificaron **205 vacantes correspondientes a 120 requerimientos** actualmente en curso.
- **Julio concentró el mayor volumen de demanda**, con 97 vacantes vigentes.
- Los perfiles con mayor cantidad de vacantes en curso fueron **Data Engineer, Analista QA y Analista Programador COBOL**.
- El nivel **Senior** representa el nivel de perfil más solicitado.
- Se identificaron **69 colaboradores disponibles**, destacando los perfiles de **Analista Programador** y **Analista de Soporte de Aplicaciones**.
- El análisis de posible cobertura permitió identificar **5 vacantes potencialmente cubribles**, equivalentes al **2.43% de las 205 vacantes analizadas**.
- Se identificó un **déficit de 136 colaboradores** respecto a las necesidades de cobertura evaluadas.
- Entre los perfiles con mayor dificultad de cobertura se identificaron **Java Backend** y **AI Engineer**.

  ## 🔄 Proceso de análisis

El desarrollo del dashboard siguió un flujo de trabajo orientado a la transformación, modelamiento y análisis de los datos:

1. **Preparación de datos:** organización y revisión de la información proveniente de Excel.
2. **Limpieza y transformación:** tratamiento de datos mediante Power Query para mejorar la calidad y estructura de la información.
3. **Modelamiento:** organización de las tablas y relaciones necesarias para el análisis.
4. **Creación de indicadores:** desarrollo de medidas y cálculos mediante DAX.
5. **Visualización:** diseño de dashboards interactivos en Power BI.
6. **Análisis:** identificación de patrones de demanda, disponibilidad, cobertura, perfiles de mayor complejidad y posibles brechas.

## 💡 Principales aprendizajes

Este proyecto permitió fortalecer conocimientos en:

- Limpieza y transformación de datos mediante Power Query.
- Modelamiento de datos para análisis en Power BI.
- Creación de medidas e indicadores utilizando DAX.
- Diseño de dashboards orientados a necesidades de negocio.
- Análisis de cobertura y disponibilidad de recursos.
- Identificación de patrones de demanda y perfiles de difícil cobertura.
- Transformación de datos en información útil para la toma de decisiones.

## 📷 Vista del dashboard

### Panel de control general RQ En curso

![Panel de control general RQ En curso](Panel%20General%20RQ%20En%20curso.png)

### Colaboradores Disponibles

![Colaboradores Disponibles](Panel%20UGR%20Disponibles.png)

### Posible Cobertura de RQ En Curso

![Posible Cobertura de RQ En Curso](Panel%20Cobertura%20RQ%20Automatizado.png)

## 📁 Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Informe RQ en curso-1.pbix` | Archivo principal del proyecto desarrollado en Power BI |
| `Panel General RQ En curso.png` | Vista general del seguimiento de requerimientos |
| `Panel UGR Disponibles.png` | Vista del análisis de colaboradores disponibles |
| `Panel Cobertura RQ Automatizado.png` | Vista del análisis de posible cobertura de vacantes |

## ⚠️ Nota sobre los datos

Los datos utilizados en la versión publicada de este proyecto han sido anonimizados y/o modificados con fines demostrativos y de portafolio.

No se incluye información confidencial, personal o sensible.

---

**Proyecto desarrollado como parte de mi portafolio de análisis de datos.**
