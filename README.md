# Estrategia de Retención de Clientes para Model Fitness

## Descripción del Proyecto

En este proyecto, se trabajó con los datos de la cadena de gimnasios Model Fitness para desarrollar una estrategia basada en datos que mejore la retención de clientes. La meta principal fue predecir la probabilidad de pérdida de clientes y analizar los factores que contribuyen a dicha pérdida.

## Objetivos

1. Predecir la probabilidad de que un cliente cancele su membresía en el próximo mes.
2. Identificar y describir grupos de clientes con comportamientos similares utilizando técnicas de clustering.
3. Analizar los factores que impactan la pérdida de clientes.
4. Proporcionar recomendaciones para mejorar la retención de clientes.

## Descripción de los Datos

El dataset utilizado contiene información sobre los clientes de Model Fitness, incluyendo:

- `gender`: Género del cliente.
- `Near_Location`: Si el cliente vive o trabaja cerca del gimnasio.
- `Partner`: Si el cliente trabaja en una empresa asociada.
- `Promo_friends`: Si el cliente se inscribió utilizando un código promocional de un amigo.
- `Phone`: Si el cliente proporcionó su número de teléfono.
- `Age`: Edad del cliente.
- `Lifetime`: Tiempo en meses desde que el cliente se unió al gimnasio.
- `Contract_period`: Duración del contrato (1 mes, 3 meses, 6 meses, 1 año).
- `Month_to_end_contract`: Meses restantes para que expire el contrato.
- `Group_visits`: Participación en clases grupales.
- `Avg_class_frequency_total`: Frecuencia media de visitas por semana a lo largo de la vida del cliente.
- `Avg_class_frequency_current_month`: Frecuencia media de visitas por semana durante el mes en curso.
- `Avg_additional_charges_total`: Cantidad total gastada en servicios adicionales.
- `Churn`: Indicador de cancelación de membresía.

## Análisis Realizado

1. **Análisis Exploratorio de Datos (EDA):**
   - Se analizaron las características principales del dataset, identificando valores promedio y distribuciones.
   - Se examinaron las diferencias entre los clientes que cancelaron y los que permanecieron.
   - Se crearon visualizaciones como histogramas y una matriz de correlación.

2. **Modelado Predictivo:**
   - Se construyeron modelos de regresión logística y bosques aleatorios para predecir la cancelación de clientes.
   - Los modelos se evaluaron utilizando métricas como exactitud, precisión y recall.
   - Se comparó el desempeño de ambos modelos.

3. **Clustering de Clientes:**
   - Se estandarizaron los datos y se aplicó el algoritmo K-means para segmentar a los clientes en grupos.
   - Se analizaron los valores medios de las características en los distintos clústeres.
   - Se calculó la tasa de cancelación para cada clúster.

4. **Conclusiones y Recomendaciones:**
   - Se realizaron recomendaciones para mejorar la retención de clientes basadas en los resultados del análisis.
   - Se identificaron los grupos de clientes más propensos a cancelar y se sugirieron estrategias para cada uno.

## Conclusiones

Las recomendaciones proporcionadas están enfocadas en mejorar la retención de clientes a través de estrategias dirigidas, como programas de fidelización, ofertas personalizadas, y seguimiento proactivo a clientes en riesgo de cancelación.
