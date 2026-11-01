# Fairness in Graph-Based Learning

**Atlas interactivo sobre equidad en aprendizaje basado en grafos**

[![Portada de Fairness in Graph-Based Learning](og-cover.png)](https://marcofmayta.github.io/Fairness-in-GBL-MM/)

**[Explorar el atlas interactivo](https://marcofmayta.github.io/Fairness-in-GBL-MM/)** · [Código fuente](https://github.com/marcofmayta/Fairness-in-GBL-MM) · [Bibliografía en el atlas](https://marcofmayta.github.io/Fairness-in-GBL-MM/#literatura)

---

## Presentación

Los modelos de aprendizaje basado en grafos utilizan tanto los atributos de las observaciones como las relaciones entre ellas. Esa información estructural puede mejorar tareas como la clasificación de nodos o la predicción de enlaces, pero también puede incorporar y propagar desigualdades presentes en los datos.

**Fairness in Graph-Based Learning** reúne conceptos, formulaciones, métodos y referencias para estudiar la equidad algorítmica en este contexto. Su objetivo es facilitar la exploración del campo, desde las métricas de clasificación hasta los efectos de la homofilia y de la propagación de mensajes en redes neuronales de grafos (*Graph Neural Networks*, GNNs).

El proyecto comprende un **atlas web interactivo** y una **colección progresiva de notebooks didácticos**. El atlas puede utilizarse directamente desde el navegador, sin instalación.

## Contenido del atlas

El recorrido está organizado en **6 ejes temáticos, 24 subáreas y 72 temas específicos**. Combina explicaciones breves, expresiones matemáticas, bibliografía y recursos para experimentar con conceptos fundamentales.

| Recurso | Qué permite explorar |
| --- | --- |
| **Taxonomía interactiva** | Navegar entre ejes, subáreas y conceptos relacionados con fairness en grafos. |
| **Fundamentos** | Repasar representación de grafos, agregación de vecinos, predicción y criterios de equidad. |
| **Simulador de redes** | Modificar la preferencia de conexión entre grupos, las capas de propagación y el descarte de aristas en una red sintética. |
| **Explorador de métricas** | Comparar *statistical parity*, *equal opportunity*, *equalized odds* y valor predictivo positivo bajo distintos escenarios. |
| **Métodos de mitigación** | Identificar intervenciones sobre los datos, la estructura, el entrenamiento y las predicciones. |
| **Biblioteca de literatura** | Buscar y filtrar referencias vinculadas con el campo. |
| **Glosario y cuestionario** | Repasar conceptos y comprobar su comprensión. |

### Simulaciones y alcance

Las visualizaciones del atlas tienen **propósitos educativos**. El simulador emplea datos sintéticos y reglas simplificadas de difusión; **no entrena una GNN real** ni reproduce integralmente métodos de investigación como FairDrop. Sus resultados no deben interpretarse como evidencia empírica de superioridad de un algoritmo ni como conclusiones transferibles a aplicaciones reales.

Las métricas de equidad ilustran criterios distintos, que pueden entrar en conflicto. Su interpretación depende de las tasas base, de los grupos considerados, del umbral de decisión y del contexto de uso.

## Notebooks: itinerario de trabajo

La colección de notebooks complementa el atlas con ejercicios y experimentos reproducibles. El itinerario contempla los siguientes temas; la disponibilidad de los cuadernos se actualizará conforme se publiquen.

| Nº | Tema | Enfoque previsto |
| :---: | --- | --- |
| 01 | Métricas de equidad | Paridad estadística, igualdad de oportunidad, igualdad de probabilidades, valor predictivo positivo y umbrales. |
| 02 | Homofilia y sesgo estructural | Mezcla entre grupos, asortatividad y composición de vecindarios. |
| 03 | Propagación del sesgo en GNNs | Agregación de mensajes y comparación de arquitecturas. |
| 04 | FairDrop y edición de aristas | Modificación de la estructura y evaluación de sus efectos. |
| 05 | Regularización y optimización multiobjetivo | Compromisos entre desempeño predictivo y equidad. |
| 06 | Equidad individual y contrafactual | Similitud entre individuos y supuestos contrafactuales. |
| 07 | Equidad en predicción de enlaces | Desigualdades en la formación y predicción de conexiones. |
| 08 | Equidad ante cambios de distribución | Robustez y transferencia frente a variaciones en los datos y el grafo. |

Los notebooks se incorporan progresivamente al repositorio, con sus dependencias, datos e instrucciones de ejecución.

## Cómo utilizarlo

**En línea:** abre [Fairness in Graph-Based Learning](https://marcofmayta.github.io/Fairness-in-GBL-MM/) desde un navegador de escritorio o móvil.

**En local:** clona el repositorio y abre `index.html` en un navegador:

```bash
git clone https://github.com/marcofmayta/Fairness-in-GBL-MM.git
cd Fairness-in-GBL-MM
```

El atlas es una página estática y se puede consultar sin instalar Python ni configurar un servidor. Los notebooks cuentan con instrucciones específicas cuando están disponibles.

## Bibliografía inicial

Estas lecturas ofrecen una introducción a las definiciones y tensiones entre distintos criterios de equidad:

- Hardt, M., Price, E., & Srebro, N. (2016). [*Equality of Opportunity in Supervised Learning*](https://arxiv.org/abs/1610.02413).
- Barocas, S., Hardt, M., & Narayanan, A. [*Fairness and Machine Learning: Limitations and Opportunities*](https://fairmlbook.org/).

La [biblioteca del atlas](https://marcofmayta.github.io/Fairness-in-GBL-MM/#literatura) contiene referencias adicionales sobre aprendizaje basado en grafos y equidad algorítmica. Las fichas son material de orientación y no sustituyen la lectura de los artículos originales.

## Autor

**Marco Mayta**

[GitHub](https://github.com/marcofmayta) · [LinkedIn](https://www.linkedin.com/in/marco-mayta-835781170/) · [ORCID](https://orcid.org/0009-0009-6019-2925)

## Licencia

El código del repositorio se distribuye bajo la [licencia MIT](LICENSE). Las publicaciones y materiales de terceros enlazados conservan sus respectivas condiciones de uso.
