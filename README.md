# Aprendizaje no supervisado: Segmentación de Clientes

Este proyecto tiene como objetivo segmentar clientes de un conjunto de datos utilizando técnicas de clustering, específicamente el algoritmo K-Means. El análisis busca identificar patrones, tendencias y necesidades dentro de la base de datos SouthGermanCredit para mejorar la toma de decisiones en el sector financiero.

## Descripción del Proyecto

El proyecto utiliza un conjunto de datos proveniente de la base de datos **SouthGermanCredit** para segmentar clientes en distintos grupos según sus características. El algoritmo K-Means con 5 clusters fue seleccionado por ser el que proporcionó la mejor separación entre los grupos, validado con el **Silhouette Score**.

### Tareas realizadas en este proyecto:
- **Limpieza de datos:** Identificación y eliminación de valores nulos, así como la normalización de variables.
- **Selección de características:** Se seleccionaron las variables más relevantes para el modelo.
- **Aplicación de técnicas de clustering:** Implementación del algoritmo K-Means para segmentar a los clientes.
- **Validación del modelo:** Evaluación de la calidad de los clusters mediante el uso de métricas como el Silhouette Score.
- **Visualización:** Se utilizaron gráficos como el PCA (Análisis de Componentes Principales) y TSNE para visualizar los clusters en un espacio reducido.

## Instrucciones de Uso

Para ejecutar este proyecto en tu máquina local, sigue los siguientes pasos:

1. Clona este repositorio:
    ```bash
    git clone https://github.com/guinansacaw/segmentacionDeClientes.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd segmentacionDeClientes
    ```

## Licencia

Este proyecto se encuentra bajo la licencia **MIT**. Puedes ver más detalles en el archivo [LICENSE](LICENSE).

## Cita del Dataset

Los datos utilizados en este proyecto provienen del siguiente conjunto de datos:

South German Credit [Dataset]. (2020). UCI Machine Learning Repository. [https://doi.org/10.24432/C5QG88](https://doi.org/10.24432/C5QG88).

## Documentación del Proyecto

Si deseas revisar el código completo o colaborar en el proyecto, puedes visitar el repositorio en GitHub. Para más detalles sobre el código, consulta la documentación disponible en [GitHub](https://github.com/guinansacaw/segmentacionDeClientes).

## Resultados

El clustering reveló cinco segmentos de clientes con características distintas, permitiendo identificar patrones clave. Estos resultados pueden utilizarse para mejorar la toma de decisiones en marketing y gestión de riesgos en el ámbito financiero.

---

**Nota:** Si tienes alguna pregunta sobre el proyecto o necesitas más detalles, no dudes en contactarme a través de GitHub.
