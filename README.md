# Diseño, desarrollo e implementación de un sistema de clasificación de fallas usando Text Mining en servicios de mantenimiento y reparación

### Resumen
El estudio se enfoca en dar solución al problema de identificación y clasificación de las fallas
y actividades en los trabajos de mantenimiento y reparación realizados por la empresa SGS
Chile, las cuales se encuentran contenidas en campos de texto no estructurados. Para ello
se utilizaron dos técnicas de clusterización de minería de textos, Topic Modeling y K-Means,
basándose en la metodología CRISP-DM. Para empezar se obtuvo una caracterización del
negocio y de los datos, identificando el proceso de una orden de trabajo, sus atributos más
importantes y realizando un pre-procesamiento de los campos de texto no estructurados.
Posteriormente, se procedió a modelar ambos algoritmos. En primer lugar, para Topic
Modeling, después de generar múltiples modelos, se determinó que el mejor modelo fue
LDA Mallet con 24 tópicos, donde cada tópico representó una falla o actividad. En base a
esto se crearon módulos de visualización para representar las principales fallas y tareas por
atributo. Paralelamente, se diseñó un algoritmo basado en K-Means que permitió conocer
el detalle técnico y el contexto de a la información obtenida. A diferencia de LDA que se
aplicó una sola vez y a la totalidad de los registros, K-Means está pensado para ejecutarse
tantas veces como atributos se quiera analizar, por lo tanto el mejor modelo se determina
en función del atributo seleccionado. Los clusters encontrados por K-Means se visualizan
en formato texto. Se concluye que ambos algoritmos contribuyen de manera conjunta en el
proceso de planificación estratégica y toma de decisiones del sector, ya que por medio de
LDA se pueden identificar patrones generales y fáciles de representar, mientras que con KMeans es posible entender el contexto y el motivo detrás de cada falla o actividad.

**Palabras clave:** Minería de textos, clusterización, modelamiento de tópicos, k-medias,
clasificación de fallas y actividades, mantención y reparación.

### Abstract
The study seeks for a solution to the problem of identification and classification of faults and
activities in the maintenance and repair work done by SGS Chile, which are contained in
unstructured text fields. For this purpose, two text mining clustering techniques were used,
Topic Modeling and K-Means, based on the CRISP-DM methodology. Initially a
characterization of the business and data was obtained, identifying the general process of a
work order, its most important attributes and performing a pre-processing of the unstructured
text fields. Subsequently, both algorithms were modeled. First, for Topic Modeling, after
generating multiple models, it was determined that the best model was LDA Mallet with 24
topics, where each topic represented a fault or activity. Based on this, visualization modules
were created that allowed to identify the main failures and tasks by attribute, in a general
and easily interpretable way. At the same time, an algorithm based on K-Means was
designed that allowed to know the technical detail of the information obtained by the previous
algorithm, by preserving the context and semantics of each observation. Unlike LDA that
was applied only once and to all the database, K-Means is designed to be executed as many
times as attributes to be analyzed, so the best model is determined according to the selected
attribute. The clusters found by K-Means are displayed in text format. It is concluded that
both algorithms contribute together in the strategic planning and decision making process,
since through LDA it is possible to identify general patterns and easy to represent, while with
K-Means it is possible to know the context and the reason behind each failure or activity.

**Keywords:** Text mining, clustering, topic modeling, k-means, classification of faults and
activities, maintenance and repair.
