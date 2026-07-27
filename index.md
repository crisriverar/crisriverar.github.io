
# Perfil profesional

Data Analyst Junior bilingüe con más de 6 años de experiencia en operaciones y servicio al cliente en entornos internacionales. Experiencia en análisis, limpieza y visualización de datos utilizando Python (pandas, NumPy), SQL y Power BI. Experiencia en análisis de datos operativos, mejora de procesos y gestión de información. Capacidad para traducir requerimientos de negocio en soluciones analíticas, identificar tendencias y optimizar el rendimiento mediante el uso de datos.

## Habilidades técnicas

- Análisis y manipulación de datos con **Python (pandas, NumPy)**
- Consultas y gestión de bases de datos con **SQL (MySQL)**
- Visualización de datos con **Tableau, Power BI, Matplotlib y Seaborn**
- Manejo avanzado de **Excel y Google Sheets**
- Diseño y análisis de **A/B Testing**

### Datos de contacto
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-001C4D?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristian-riverar)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-001C4D?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:cristianrivera.r@hotmail.com)

---

# Proyectos seleccionados

## Análisis de funnel y experimentación A/B para RappiPlus

Este proyecto evalúa **RappiPlus**, un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario. Se construyó un pipeline de limpieza reproducible, se analizó el funnel de conversión y retención por cohortes, y se evaluó el impacto de un cambio de diseño mediante un test A/B.

#### Herramientas y tipo de proyecto

![Python](https://img.shields.io/badge/Python-001C4D?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-001C4D?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-001C4D?style=for-the-badge&logo=mysql&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-001C4D?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-001C4D?style=for-the-badge)
![Análisis de cohortes](https://img.shields.io/badge/Análisis_de_cohortes-001C4D?style=for-the-badge)
![Tests A/B](https://img.shields.io/badge/Tests_A%2FB-001C4D?style=for-the-badge)
![Análisis de funnel](https://img.shields.io/badge/Análisis_de_funnel-001C4D?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-001C4D?style=for-the-badge&logo=powerbi&logoColor=white)

### Preguntas clave

1. ¿Qué categorías de producto concentran la mayor parte de la ganancia?
2. ¿En qué etapa del funnel se pierden más usuarios?
3. ¿El cambio en el diseño del checkout mejora la conversión de forma significativa?
4. ¿Cuál es la eficiencia del gasto en marketing por canal?

### Metodología

- **Calidad de datos y KPIs:** Revisión de calidad sobre órdenes, catálogo y gasto en marketing.
- **Análisis de funnel:** Cálculo de tasas de abandono entre etapas usando datos de eventos y actividad de usuario.
- **Retención por cohortes:** Evaluación de si los usuarios regresan tras el registro.
- **Test A/B:** Comparación estadística de dos versiones del checkout (prueba de hipótesis, valor p).

### Conclusiones y recomendaciones

- El 83% de la ganancia total proviene de la categoría Electrónica, concentrada en un solo producto (Laptop Gaming 16GB), lo que representa un riesgo de dependencia. Se recomienda diversificar el catálogo promocionado.
- La mayor caída del funnel (13.29%) ocurre entre "begin checkout" y "add payment info", señal de fricción en el proceso de pago más que falta de interés del usuario.
- La versión B del checkout mostró una conversión 0.60% mayor, pero sin significancia estadística (p = 0.42); se recomienda extender el test antes de escalar el cambio.
- Con un margen neto de 11.51%, se recomienda redirigir inversión de marketing hacia los canales con mejor retorno relativo.

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/crisriverar/Analisys-RappiPlus-).**

## Análisis de datos de telecomunicaciones para ConnectaTel

Este proyecto analiza el comportamiento de uso de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia, integrando tres fuentes de datos distintas para construir un perfil estadístico del uso del servicio (llamadas y mensajes) por cliente y por segmento demográfico. El objetivo es **detectar oportunidades comerciales** a partir de patrones de consumo y comportamiento atípico.

#### Herramientas y tipo de proyecto

![Python](https://img.shields.io/badge/Python-001C4D?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-001C4D?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-001C4D?style=for-the-badge&logo=numpy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-001C4D?style=for-the-badge)
![Detección de outliers](https://img.shields.io/badge/Detección_de_outliers-001C4D?style=for-the-badge)
![Segmentación](https://img.shields.io/badge/Segmentación_de_clientes-001C4D?style=for-the-badge)
![Análisis exploratorio](https://img.shields.io/badge/EDA-001C4D?style=for-the-badge)

### Preguntas clave

1. ¿Cómo integrar y limpiar bases de datos provenientes de tres fuentes distintas?
2. ¿Qué segmentos de clientes concentran el mayor nivel de uso del servicio?
3. ¿Existen comportamientos atípicos (outliers) que representen oportunidades comerciales?

### Metodología

- **Preprocesamiento de datos:** Validación, estandarización de tipos de datos y detección de valores inconsistentes en tres fuentes (planes, usuarios y uso real).
- **Análisis exploratorio (EDA):** Construcción de un perfil estadístico del uso por cliente y por segmento demográfico.
- **Detección de outliers:** Identificación de comportamientos atípicos mediante métodos estadísticos y visuales.
- **Segmentación:** Agrupación de clientes por edad, país y comportamiento de uso.

### Conclusiones y recomendaciones

- El segmento de adultos concentra el mayor nivel de uso del servicio, siendo un cliente potencial clave para campañas de migración a planes premium.
- El segmento de adultos mayores, aunque más pequeño, muestra mayor estabilidad económica y es candidato a estrategias de fidelización.
- El bajo uso registrado en el segmento joven podría estar subestimado, ya que el análisis no incluye consumo de datos móviles, canal probablemente dominante en ese grupo.
- Se identificó un grupo de usuarios con consumo significativamente superior al promedio, con potencial para planes premium o categorías VIP.
- Se recomienda priorizar estrategias de upselling sobre adultos y adultos mayores para mejorar el ingreso promedio por usuario (ARPU).

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/crisriverar/ConnectaTel).**

---

Hosted on GitHub Pages
