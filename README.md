# Fairness in Graph-Based Learning

**Un atlas interactivo para estudiar la equidad en el aprendizaje basado en grafos.**

[![Fairness in Graph-Based Learning](og-cover.png)](https://marcofmayta.github.io/Fairness-in-GBL-MM/)

[Explorar el atlas](https://marcofmayta.github.io/Fairness-in-GBL-MM/) · [Código fuente](https://github.com/marcofmayta/Fairness-in-GBL-MM) · [Consultar la bibliografía](https://marcofmayta.github.io/Fairness-in-GBL-MM/#literatura)

## Sobre el proyecto

En el aprendizaje basado en grafos, una predicción no depende solo de las características de un nodo. También intervienen sus vecinos y la forma en que están conectados. Esto permite aprovechar información que los modelos tradicionales no siempre capturan, pero plantea un problema: las relaciones de una red también pueden reflejar desigualdades, segregación o sesgos presentes en los datos.

Preparé este atlas para reunir y explicar conceptos que suelen estudiarse por separado: métricas de equidad, homofilia, propagación de mensajes, fuentes de sesgo y métodos para mitigarlo. La idea es poder pasar de una definición a una fórmula y, cuando sea posible, observar su comportamiento en un ejemplo interactivo.

El sitio está pensado para estudiantes, docentes e investigadores que trabajan con aprendizaje automático y grafos. No requiere instalación.

## Qué encontrarás en el atlas

El contenido se distribuye en **6 ejes, 24 subáreas y 72 temas**.

| Sección | Contenido |
| --- | --- |
| **Fundamentos** | Grafos, agregación de mensajes, predicción y criterios de equidad. |
| **Taxonomía** | Un mapa de conceptos para recorrer las áreas y sus relaciones. |
| **Simulador** | Una red sintética en la que puedes modificar la preferencia de conexión entre grupos, la profundidad de propagación y el descarte de aristas. |
| **Métricas** | Comparaciones entre *statistical parity*, *equal opportunity*, *equalized odds* y valor predictivo positivo. |
| **Métodos** | Técnicas que actúan sobre los datos, la estructura del grafo, el entrenamiento o las predicciones. |
| **Literatura** | Referencias científicas con opciones de búsqueda y filtrado. |
| **Glosario y preguntas** | Definiciones y ejercicios para repasar lo aprendido. |

### Sobre las simulaciones

El simulador utiliza datos sintéticos y reglas simplificadas de difusión. No entrena una red neuronal de grafos ni implementa por completo métodos como FairDrop. Sirve para observar relaciones entre estructura, propagación y resultados de clasificación, no para comparar el rendimiento real de algoritmos.

Las diferencias entre métricas también requieren cuidado: una brecha pequeña bajo un criterio no garantiza equidad bajo los demás. Las tasas base, el umbral de decisión y el contexto influyen en la interpretación.

## Notebooks

El atlas se complementa con una serie de notebooks. Los temas previstos son los siguientes; cada cuaderno estará disponible en el repositorio cuando se publique.

| Nº | Tema | Contenido |
| :---: | --- | --- |
| 01 | Métricas de equidad | Paridad estadística, igualdad de oportunidad, *equalized odds*, valor predictivo positivo y umbrales. |
| 02 | Homofilia y sesgo estructural | Conexiones entre grupos, asortatividad y composición de vecindarios. |
| 03 | Propagación del sesgo en GNNs | Agregación de mensajes y diferencias entre arquitecturas. |
| 04 | FairDrop y edición de aristas | Intervenciones sobre las conexiones y sus efectos. |
| 05 | Regularización y optimización multiobjetivo | Relación entre desempeño predictivo y equidad. |
| 06 | Equidad individual y contrafactual | Similitud entre individuos y supuestos contrafactuales. |
| 07 | Equidad en predicción de enlaces | Sesgos en la formación y predicción de relaciones. |
| 08 | Equidad ante cambios de distribución | Robustez y transferencia cuando cambian los datos o la estructura. |

## Cómo acceder

Puedes usar el [atlas en línea](https://marcofmayta.github.io/Fairness-in-GBL-MM/) desde el navegador. Para abrir una copia local:

```bash
git clone https://github.com/marcofmayta/Fairness-in-GBL-MM.git
cd Fairness-in-GBL-MM
```

Después, abre `index.html`. La página funciona sin instalar Python. Los notebooks tendrán sus propias dependencias e instrucciones de ejecución.

## Lecturas de referencia

- Hardt, M., Price, E., & Srebro, N. (2016). [*Equality of Opportunity in Supervised Learning*](https://arxiv.org/abs/1610.02413).
- Barocas, S., Hardt, M., & Narayanan, A. [*Fairness and Machine Learning: Limitations and Opportunities*](https://fairmlbook.org/).

En la sección [Literatura](https://marcofmayta.github.io/Fairness-in-GBL-MM/#literatura) del atlas hay más trabajos sobre equidad algorítmica y aprendizaje en grafos. Las fichas ofrecen una introducción a cada referencia; para profundizar en un método o resultado es necesario consultar el artículo original.

## Autor

**Marco Mayta**

[GitHub](https://github.com/marcofmayta) · [LinkedIn](https://www.linkedin.com/in/marco-mayta-835781170/) · [ORCID](https://orcid.org/0009-0009-6019-2925)

## Licencia

El código se distribuye bajo la [licencia MIT](LICENSE). Las publicaciones enlazadas pertenecen a sus respectivos autores.
