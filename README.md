# Análisis Visual de la Brecha Salarial de Género y el Sector STEM en Europa

Repositorio con el código, los conjuntos de datos y la documentación técnica utilizados para la Práctica Final de la asignatura de Visualización de Datos del Máster de Ciencia de Datos de la UOC.

## Enlaces del Proyecto

* **Visualización Interactiva (Infogram):** [AÑADE TU ENLACE AQUÍ]
* **Presentación Audiovisual (Vídeo):** [AÑADE TU ENLACE AQUÍ]

## Descripción del Proyecto

Este proyecto analiza mediante visualización de datos la evolución de la brecha salarial de género en la Unión Europea (2013-2022), contrastándola con la tasa de mujeres graduadas en disciplinas STEM. La narrativa visual explora la rigidez estructural de la desigualdad y analiza anomalías sectoriales específicas, como la alta disparidad en el sector tecnológico y la brecha invertida en el sector de la construcción.

## Fuentes de Datos

Los datos utilizados han sido extraídos de fuentes oficiales, procesados e integrados mediante cruces relacionales en Python:
* **Eurostat:** Datos de brecha salarial general (`sdg_05_20`), brecha salarial por sector NACE Rev. 2 (`earn_gr_gpgr2`) y graduados en educación terciaria (`educ_uoe_grad04`).
* **World Economic Forum (WEF):** Índice Global de Brecha de Género (GGGI), obtenido a través del Instituto QoG.

## Estructura de este Repositorio

* `/notebooks`: Contiene el código en Python (Jupyter Notebook) utilizado para la limpieza, análisis exploratorio (EDA), integración del índice WEF y generación de *Data Marts* específicos.
* `/data`: Contiene los micro-datasets optimizados en formato CSV utilizados para alimentar las gráficas interactivas.

## Herramientas Utilizadas

* **Procesamiento de Datos:** Python (Pandas).
* **Análisis Exploratorio:** Matplotlib, Seaborn.
* **Visualización Final y Narrativa:** Infogram.
