# 📈 Expansión Estratégica de Biogenesys en LATAM

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python" />
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="powerbi" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/Folium-333333?style=for-the-badge&logo=leaflet&logoColor=white" alt="folium" />
</p>

## 1. Resumen del Proyecto

Este proyecto presenta un análisis de datos sobre el impacto de la pandemia de COVID-19 y las campañas de vacunación en seis países clave de América Latina: Argentina, Brasil, Chile, Colombia, México y Perú. El objetivo principal fue identificar, a partir de estos datos, las ubicaciones óptimas para una potencial expansión de los laboratorios farmacéuticos de la empresa BIOGENESYS.

## 2. Contexto del Negocio

En este escenario, BIOGENESYS busca expandir sus operaciones para mejorar el acceso a vacunas y tratamientos en la región. Una decisión de expansión de esta magnitud requiere una inversión significativa, por lo que es crucial basarla en evidencia sólida. Este análisis provee el fundamento cuantitativo para minimizar el riesgo y maximizar el impacto de la inversión.

## 3. Fuente de Datos

La metodología se centró en un conjunto de datos en formato CSV que contenía información diaria sobre casos de COVID-19, muertes, vacunación y variables demográficas y socioeconómicas. El análisis se enfocó en datos posteriores al 1 de enero de 2021.

## 4. Flujo de Trabajo y Metodología

El proyecto siguió un ciclo de vida de análisis de datos completo:

* **1. Limpieza y Transformación de Datos:** Se procesó el dataset utilizando Python (Pandas). Las tareas incluyeron la conversión de tipos de datos y la creación de columnas calculadas relevantes, como medias móviles de 7 días, tasas de crecimiento y cobertura de vacunación por 100 personas. El resultado fue un dataset enriquecido y listo para el análisis.

* **2. Análisis Exploratorio de Datos (EDA):** Se utilizó Python para realizar un análisis profundo que reveló insights clave, como el impacto heterogéneo de la pandemia entre países, el desacoplamiento entre casos y mortalidad en olas posteriores, y el diverso desempeño de las campañas de vacunación.

* **3. Desarrollo de Dashboard en Power BI:** Se construyó un dashboard interactivo con tres pestañas para facilitar la navegación y el storytelling. El dashboard permite explorar el panorama general, la cobertura de vacunación y los factores demográficos para la expansión.

* **4. Análisis Geoespacial:** Se desarrolló un mapa interactivo con la librería Folium en Python. Este mapa visualiza los países de estudio con marcadores circulares cuyo tamaño es proporcional al número de casos, ofreciendo una perspectiva adicional sobre la magnitud del impacto en la región.

## 5. Herramientas Utilizadas

* **Lenguaje de Programación:** Python
* **Librerías de Python:** Pandas, Matplotlib, Seaborn, Folium
* **Business Intelligence:** Power BI
* **Entorno de Desarrollo:** Jupyter Notebooks, Visual Studio Code

## 6. Resultados y Conclusiones Estratégicas

El análisis permitió perfilar las ubicaciones óptimas para la expansión de BIOGENESYS, clasificándolas por nivel de prioridad:

* **Alta Prioridad:**
    * **Chile:** Destaca por su excepcional ejecución de la campaña de vacunación, una población más envejecida que sugiere una demanda sostenida, y una infraestructura sanitaria robusta.
    * **Perú:** Mostró una notable capacidad de aceleración en su vacunación y su población más joven presenta una buena disposición, convirtiéndolo en un candidato interesante.

* **Consideración Estratégica:**
    * **Brasil y Argentina:** Representan mercados de gran escala con necesidades continuas, aunque la evaluación de su infraestructura es clave.

* **Oportunidad con Análisis Adicional:**
    * **Colombia:** Presenta un mercado en crecimiento potencial debido a su población joven y una capacidad de vacunación que fue mejorando.

## 7. Estructura del Repositorio

El repositorio está organizado de la siguiente manera para facilitar su navegación y entendimiento:

*-Notebooks/         # Contiene los Jupyter Notebooks con el código de análisis
*-Power_bi/          # Contiene el archivo .pbix del dashboard
*-Reports/           # Contiene el informe final del proyecto
*-README.md

## 8. Cómo Replicar este Proyecto

1.  Clona este repositorio en tu máquina local.
2.  Ejecuta el Jupyter Notebook en la carpeta `notebooks/` para seguir el flujo de trabajo del análisis.
3.  Abre el archivo `.pbix` en la carpeta `power_bi/` con Power BI Desktop para explorar el dashboard interactivo.

## 9. Autor

* **Efrain Chapal**
    * [LinkedIn](https://www.linkedin.com/in/efrainchapal)
    * [GitHub](https://github.com/efrainchapal)
