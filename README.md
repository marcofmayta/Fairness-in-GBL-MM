# Fairness in Graph-Based Learning

**Atlas y notebooks sobre equidad en aprendizaje basado en grafos**

[Explorar el atlas](https://marcofmayta.github.io/Fairness-in-GBL-MM/) · [Ver el código](https://github.com/marcofmayta/Fairness-in-GBL-MM)

## Sobre el proyecto

Los modelos de aprendizaje basado en grafos aprovechan las relaciones entre observaciones para realizar tareas como clasificación de nodos, predicción de enlaces y representación de redes. Sin embargo, esas relaciones también pueden contener patrones de segregación o desigualdad que terminan influyendo en las predicciones.

Este repositorio reúne material para estudiar *fairness* en Graph-Based Learning (GBL), desde las definiciones estadísticas hasta los métodos que intervienen sobre las características, las conexiones o el entrenamiento de modelos de grafos.

El proyecto tiene dos partes, un atlas web para explorar conceptos y métodos, y una colección progresiva de notebooks con experimentos ejemplos.

## Atlas interactivo

**[Abrir Fairness in GBL](https://marcofmayta.github.io/Fairness-in-GBL-MM/)**

El atlas presenta una organización temática del campo, con explicaciones, fórmulas, referencias y visualizaciones interactivas. Incluye:

- Definiciones de equidad grupal, individual y contrafactual.
- Fuentes de sesgo en los atributos, las etiquetas y la estructura del grafo.
- Homofilia, agregación de vecinos y propagación de información.
- Métodos de mitigación antes, durante y después del entrenamiento.
- Métricas de evaluación y sus posibles incompatibilidades.
- Simulaciones didácticas, glosario y bibliografía consultable.

Las simulaciones del atlas son ilustrativas; no son resultados empíricos de un estudio.

## Notebooks

La colección está organizada para avanzar desde métricas de clasificación hasta problemas específicos de aprendizaje en grafos. Los siguientes títulos describen el itinerario previsto; su inclusión aquí no implica que todos los archivos estén publicados.

| Nº | Tema | Contenido principal |
| --- | --- | --- |
| 01 | Métricas de equidad | Statistical parity, equal opportunity, equalized odds, predictive parity y umbrales de decisión |
| 02 | Homofilia y sesgo estructural | Mezcla entre grupos, assortativity y estructura de vecindarios |
| 03 | Propagación del sesgo en GNN | Agregación de mensajes y comparación entre arquitecturas |
| 04 | FairDrop y edición de aristas | Intervenciones sobre la estructura y sus efectos |
| 05 | Regularización y optimización multiobjetivo | Compromisos entre desempeño predictivo y equidad |
| 06 | Equidad individual y contrafactual | Similitud, sensibilidad y supuestos contrafactuales |
| 07 | Equidad en predicción de enlaces | Sesgo en la formación y predicción de relaciones |
| 08 | Equidad ante cambios de distribución | Robustez, transferencia y variaciones estructurales |

Los notebooks disponibles se incorporarán a la carpeta [`notebooks/`](notebooks/) a medida que se publiquen.

## Cómo utilizar el repositorio

Para consultar el contenido teórico no hace falta instalar nada: basta con abrir el [atlas](https://marcofmayta.github.io/Fairness-in-GBL-MM/).

Para trabajar con el código localmente:

```bash
git clone https://github.com/marcofmayta/Fairness-in-GBL-MM.git
cd Fairness-in-GBL-MM
```

El archivo `index.html` puede abrirse directamente en un navegador. Los notebooks, una vez publicados, podrán ejecutarse con Jupyter o Google Colab. Las dependencias y los datos utilizados se indicarán en cada cuaderno.

## Referencias para comenzar

- Hardt, M., Price, E., & Srebro, N. (2016). [Equality of Opportunity in Supervised Learning](https://arxiv.org/abs/1610.02413).
- Barocas, S., Hardt, M., & Narayanan, A. [Fairness and Machine Learning](https://fairmlbook.org/).

El atlas contiene otras referencias relacionadas con fairness y aprendizaje en grafos.

## Autor

**Marco Mayta**

[GitHub](https://github.com/marcofmayta) · [LinkedIn](https://www.linkedin.com/in/marco-mayta-835781170/) · [ORCID](https://orcid.org/0009-0009-6019-2925)

## Licencia

El repositorio incluye una [licencia MIT](LICENSE).
