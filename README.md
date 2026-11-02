# Executive-HR-Compensation-Analytics-Dashboard
Un tablero analítico ejecutivo de Business Intelligence de dos páginas desarrollado en Power BI Desktop, diseñado para la gestión estratégica del talento, control de rotación, análisis de desempeño y optimización de estructuras salariales corporativas.

 Stack Tecnológico y Arquitectura

* **Herramientas:** Power BI Desktop, Power Query, DAX Studio / Motor DAX.
* **Modelado de Datos:** Esquema en Estrella (*Star Schema*) normalizado con tablas de dimensiones y hechos longitudinales.
* **Diseño UI/UX:** Paleta corporativa Verde/Teal/Coral, estructura en cuadrícula modular (2x2), tarjetas KPI con formato numérico dinámico y navegación lateral intuitiva.

---

## Estructura Técnica y Funcional del Tablero

### Página 1: Capital Humano, Talento y Rotación
Diseñada para la gerencia de operaciones y recursos humanos con el fin de medir la estabilidad de la plantilla y el rendimiento general.

* **KPIs Principales (Tarjetas Superiores):**
  * **Total Empleados:** 4,256 colaboradores activos e históricos analizados.
  * **Empleados Fijos:** 2,491 colaboradores bajo régimen efectivo.
  * **Empleados por Contrato:** 1,715 colaboradores bajo modalidad de servicios/horas.
  * **Empleados sin Registro:** 50 casos bajo auditoría de datos.
  * **Tasa de Rotación Global:** 13,46%.
* **Visuales y Gráficos Clave:**
  * **Tasa de Rotación por Departamento:** Gráfico de barras que identifica las áreas críticas (Operaciones y Ventas liderando la rotación).
  * **Total de Empleados por Evaluación:** Distribución de calificaciones de desempeño (Bueno, Excelente, Regular, Malo).
  * **Empleados con Alto Desempeño Rotados:** Análisis longitudinal de tendencias (2020–2024).
  * **Composición por Categoría:** Gráfico de anillos (*Donut Chart*) con los pesos porcentuales de la plantilla (58.53% Fijos, 40.3% Contratados).
![Página 1](./images/Dash1.png)

---

### Página 2: Compensación, Nómina y Estructura Salarial
Enfocada en el análisis financiero y control presupuestario de la masa salarial y costos operativos.

* **KPIs Financieros y Buscador Dinámico:**
  * **Costo Promedio Empleados Fijos:** $121,110.79.
  * **Costo Promedio Empleados Contratados:** $7,438.14.
  * **Buscador de Empleados:** Segmentador interactivo optimizado por nombre completo para auditoría y consulta de perfiles individuales.
* **Visuales y Gráficos Clave:**
  * **Cantidad de Empleados y Costo Promedio por Desempeño:** Combinación de columnas y líneas que evalúa la meritocracia salarial.
  * **Costo de Hora Extra por Departamento:** Gasto acumulado en horas extraordinarias de contratados (Operaciones y Ventas con mayor volumen de inversión).
  * **Costo Promedio por Tipo de Empleado:** Desglose porcentual del impacto financiero (94.21% asignado a efectivos).

---
