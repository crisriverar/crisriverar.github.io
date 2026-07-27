## Acerca de mí
Economista y financiera certificada en análisis de datos con sólida experiencia en extracción, limpieza y modelado de datos estratégicos.

Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, logrando ahorros significativos de tiempo mediante la automatización.

Habilidades tecnológicas
Análisis y gestión de datos utilizando Excel / SQL / Python / R
Visualización de datos y narración de historias usando Tableau
Habilidades blandas
Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos

LinkedIn Outlook

Proyectos seleccionados
Análisis de retención de clientes para gimnasio
En todas las industrias, la retención de clientes es fundamental para garantizar ingresos sostenibles y reducir los costos asociados con la adquisición de nuevos clientes. Identificar los factores clave que influyen en la retención y cancelación permite al gimnasio Model Fitness anticiparse a los riesgos de abandono, diseñar estrategias de fidelización efectivas y personalizar las experiencias para cada cliente.

Herramientas y tipo de proyecto
Python Pandas Seaborn scikit-learn Limpieza de datos Transformación de datos Análisis de datos Modelos de predicción

Preguntas clave
¿Qué factores demográficos o de comportamiento influyen más en la cancelación?
¿Qué características diferencian a los clientes leales de los que abandonan?
¿Cómo se pueden segmentar los clientes para diseñar estrategias personalizadas?
Metodología
Preprocesamiento de datos: Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
Explorartory Data Analysis (EDA): Se analizaron características demográficas y de uso, identificando patrones en clientes que permanecen y los que cancelan.
Modelado predictivo: Se entrenaron modelos de regresión logística y bosque aleatorio para predecir la cancelación de clientes con un precisión del 85% y 84%, respectivamente.
Clustering: Se segmentaron los clientes en grupos utilizando K-means para identificar comportamientos similares.
Conclusiones y recomendaciones
Factores críticos de retención:
La proximidad al gimnasio, contratos más largos, la participación en sesiones grupales y mayor frecuencia de visitas están fuertemente asociados con una menor tasa de cancelación.
Clientes jóvenes, con contratos cortos y baja frecuencia de visitas, tienen mayores tasas de cancelación.
Estrategias recomendadas:
Extender contratos cortos: Ofrecer incentivos para ampliar contratos de 1 mes.
Promover actividades grupales: Diseñar campañas que destaquen los beneficios de participar en sesiones grupales.
Campañas personalizadas: Utilizar el modelo predictivo para identificar clientes en riesgo y ofrecer promociones específicas.
Segmentación proactiva: Clasificar clientes nuevos por edad y duración de contrato para diseñar estrategias de retención desde el inicio.
Visualizaciones destacadas
Distribución de cancelación según duración del contrato: Observamos que quienes cancelaron suelen contratar en su mayoría 1 mes, al igual que quienes no cancelan. Sin embargo, quienes permanecen suelen también contratar por periodos de 1 año y 6 meses, mientras que los que cancelan en su minoría contratan en dichos periodos. Contract Period Histogram
Matriz de correlaciones: Se encontró que Las características month_to_end_contract y contract_period están altamente correlacionadas (0.9), lo que sugiere que se debe tener cuidado con la multicolinealidad al desarrollar modelos predictivos. Corr Matrix Churn Data
Análisis de clústeres: El dendrograma muestran cómo los clientes se agrupan en segmentos distintos basados en sus características, donde el número óptimo de clústeres sugerido es 4. Dendrogram
Explora más detalles del proyecto en el repositorio completo.

Optimización de gastos de marketing
El objetivo de este proyecto es optimizar los gastos de marketing de Y.Afisha mediante el análisis de datos de visitas, pedidos y costos publicitarios. El estudio busca comprender el comportamiento del usuario, identificar fuentes de adquisición rentables y calcular métricas clave como el Costo de Adquisición de Clientes (CAC), el Valor de Vida del Cliente (LTV) y el Retorno de la Inversión en Marketing (ROMI).

Herramientas y tipo de proyecto
Python Pandas Matplotlib Seaborn NumPy Limpieza de datos Transformación de datos Análisis de datos Análisis de cohortes Visualización de datos

Preguntas clave
¿Cuántos usuarios activos diarios, semanales y mensuales tiene la aplicación?
¿Cuáles son las principales fuentes de adquisición de clientes y su rentabilidad?
¿Qué métricas de ventas y conversiones se pueden mejorar?
¿Qué tan efectiva es cada fuente de marketing según su ROMI?
Metodología
Preprocesamiento de datos: Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
Análisis del comportamiento de usuarios Cálculo de métricas como usuarios activos diarios (DAU), semanales (WAU) y mensuales (MAU), duración de sesiones y frecuencia de retorno.
Análisis de ventas: Evaluación del tamaño promedio de compra, pedidos por cliente y LTV.
Pruebas de hipótesis: Cálculo de CAC, ROMI y costos por fuente de adquisición.
Conclusiones y recomendaciones
Comportamiento de usuarios, Ventas y Marketing:
El 16% de los usuarios regresa semanalmente, pero solo el 4% vuelve mensualmente, indicando una posible necesidad de campañas de retención.
El tamaño promedio de compra es de $5, con algunos picos en diciembre debido a promociones estacionales. La mayoría de los usuarios realiza un pedido por mes.
Las fuentes con mayor ROMI es 1, 5 y 9 pues, antes de que las cohortes cumplan el primer mes de edad, el ROMI casi alcanza el 1 en la mayoría de cohortes.
Destaca la fuente 1 donde, a pesar de ser la segunda fuente en la que menos se gasta, es 3era fuente que más usuarios atrae.
Recomendaciones:
Descontinuar las fuentes 7, 9 y 10 debido a su bajo rendimiento.
Reducir la inversión en la fuente 3, ya que no genera retornos significativos.
Invertir en la fuente 1, que sigue siendo una aliada clave con baja inversión y alto rendimiento.
Visualizaciones destacadas
Usuarios Activos Semanales (WAU): Se observa una tendencia a la alza a partir de la semana 31 de 2017, con una caída drástica en la semana 53 del mismo año. Se observa una disminución en usuarios en la semana 13, 17 y 18 de 2019. WAU Chart
LTV por cohorte: Cada cliente de la primera cohorte representó un ingreso de $11.88. Además, la cohorte de septiembre de 2017 representó ingresos de $13.44 por cliente. LTV Heat Chart
Explora más detalles del proyecto en el repositorio completo.

Análisis de comportamiento de usuarios y embudo de ventas
Este proyecto analiza el embudo de ventas de la aplicación de una empresa de alimentos para identificar las etapas con mayores pérdidas de usuarios y evalúa, mediante un experimento A/A/B, si un nuevo diseño de fuentes puede mejorar la conversión en comparación con el diseño actual. El objetivo es proporcionar insights basados en datos que guíen decisiones estratégicas sobre diseño y funcionalidad.

Herramientas y tipo de proyecto
Python Pandas Seaborn Plotly Limpieza de datos Transformación de datos Análisis de datos Tests A/B Pruebas de hipótesis Visualización de datos

Preguntas clave
¿Qué eventos del embudo de ventas tienen mayores tasas de abandono?
¿Qué porcentaje de usuarios completa el embudo de ventas desde el inicio hasta el pago?
¿El cambio en el diseño de las fuentes afecta significativamente la conversión?
¿Hay diferencias estadísticas entre los grupos de control y el grupo de prueba?
Metodología
Preprocesamiento de datos: Se ajustaron los nombres de las columnas, se eliminaron duplicados y se filtraron registros incompletos.
Análisis del embudo de ventas: Se identificaron eventos clave y la proporción de usuarios que avanzan entre etapas.
Experimentación A/A/B: Se compararon conversiones entre grupos de control y prueba mediante pruebas de hipótesis estadísticas.
Conclusiones y recomendaciones
Embudo de ventas:
El evento OffersScreenAppear es donde más usuarios abandonan (61.9%).
Solo el 47.7% de los usuarios completa el embudo de ventas hasta el pago exitoso.
Resultados del experimento:
No se encontraron diferencias estadísticas significativas entre los grupos de control y el grupo de prueba.
Las nuevas fuentes no generan un impacto positivo en la conversión, por lo que no se recomienda implementar este cambio.
Recomendaciones:
Optimizar la pantalla de ofertas para retener más usuarios en esa etapa.
Priorizar otros cambios en el diseño o funcionalidad de la aplicación con mayor potencial de impacto.
Visualizaciones destacadas
Embudo de ventas: La etapa en la que más se pierden usuarios es en el Tutorial, donde solo el 23.7% de los usuarios en la etapa anterior llegan a esta. La siguiente etapa donde se pierden más usuarios es en OfferScreenAppear, donde el 61.9% de los usuarios de la etapa anterior pasan a esta. Sales Funner Chart
Periodo de tiempo de los datos: Los datos completos están disponibles a partir del 1 de agosto de 2019, por lo que se descartaron fechas anteriores. El periodo actualizado abarca del 1 al 7 de agosto de 2019. Time Period Data
Explora más detalles del proyecto en el repositorio completo.
