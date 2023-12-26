## Data Analytics - Accidentes aéreos - 

### Descripción del proyecto

En este proyecto se asume el rol de un Data Analyst cuyo trabajo es realizar un análisis sobre un dataset de accidentes aéreos, para posteriormente disponibilizar la información en un [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTNjZWVjNzEtNzg2Zi00YTFkLWI4NmMtM2ViMjc3NjZhOWViIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSection15723a553e111322fc88) interactivo utilizando Power BI.

### Contexto

Los riesgos asociados a las activiades aeronáuticas conllevan consecuencias que pueden ser catastróficas en términos de vidas humanas y pérdidas económicas. Por ello, es crucial investigar las causas de estos accidentes y aprender a prevenirlos y mitigar los efectos en el futuro aumentando los indices de seguridad.

### Objetivo

- Realizar un análisis exploratorio de los datos en un notebook.
- Realizar un dashboard funcional y coherente con el storytelling.
- Establecer conclusiones.
- Graficar y medir 2 KPIs.
  1. Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior.
  2. Evaluar la disminución de un 5% la tasa promedio de supervivientes de los últimos 5 años, comparado con los 5 años anteriores.
- Read me con un reporte de análisis con base en los dashboards.

### Análisis Exploratorio de Datos

- Nube de palabras, Paises con más accidentes.
<img src="https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/4d58facf-7fa4-4fe6-b927-d3330b0d116c" width="800">

- Accidentes de indole militar.
<img src="https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/5bc5d507-e64a-48c2-b9bb-d3bd1b3bd26f" width="350">

- Nube de palabras, palabras más repetidas en la descripción de los accidentes.
<img src="https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/ba24a433-c590-4048-b160-872ff9e16e8b" width="600">

- Evolución del % de sobrevivientes Anual - Aviones Comerciales.
<img src="https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/0e553d17-6e7d-4d36-addf-06a7712bc1e8" width="600">

- Evolución Anual de los accidentes.
<img src="https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/c75fe17e-66e2-47d4-86be-d475d66a722e" width="600">

### Repote del análisis 
#### 1.País

En la página País, se pueden observar los accidentes segmentados por país.<br>
Se puede filtrar según el año, país, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, un promedio de la tasa de supervivencia y del total de personas a bordo por vuelo.<br>
Las diferentes gráficas permiten apreciar que Estados Unidos (USA) es el país con más cantidad de accidentes y con más fatalidades, seguida por Rusia.

![Pais](https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/2f5c5000-6cdb-4eea-9e8f-593debb2127b)

#### 2.Operador

En la página Operador, se pueden observar los accidentes segmentados por operador/empresa.<br>
Se puede filtrar según el año, país, operador, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, un promedio de los pasajeros por vuelo y la tasa de supervivencia.<br>
Las gráficas permiten apreciar que Aeroflot es la empresa con más cantidad de accidentes, seguida por la fuerza aérea estadounidense (U.S. Air Force). Ademàs, otras operadoras de este paìs se encuentran dentro del Top 6. 

![Operador](https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/b84172f9-7c8d-480a-a601-92604765c9c1)

#### 3.Aeronaves

En la página Aeronave, se pueden observar los accidentes segmentados por aeronaves, tanto en su categoría (avión, helicòptero y globo dirigible) como en su tipo (marca / modelo).<br>
Se puede filtrar según el año, país, tipo, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, diferentes tipos de aeronaves y la tasa de supervivencia.<br>
Las gráficas permiten apreciar que la mayoría de los accidentes son provocados por aviones y una lista de aeronaves con más accidentes.

![Aeronave](https://github.com/Rodzxc/P2_Data_Analytics/assets/133074545/a8a89d55-cedb-4137-b640-54a2616e0098)

### Conclusión
Interpolando la lista de aeronaves con más accidentes, las operadoras con más accidentes (Aeroflot,  U.S Air Force, United Air Lines y U.S. Army Air Force); se llega a la conclusión de que estas responden en parte a la cantidad de accidentes en los Estados Unidos y Rusia.<br>
Se mantienen marcadas tendencias a la baja en los últimos años, tanto a nivel mundial como en Estados Unidos y Rusia.<br>
El factor climático no es relevante en los accidentes de las aeronaves menos inestables como los helicópteros. 
Por último, los objetivos propuestos para los KPIs develan que son históricamente difíciles de superar y sostener a lo largo de los años; y en los años más recientes, los valores no llegan a los objetivos.


### Repositorio y archivos relevantes

En este repositorio puedes encontrar los siguientes archivos relevantes:

- AC_accidents_INPUTS.csv: Datos originales, Dataset de los accidentes de aviones, desde 1908 hasta 2021.

- ETL_AC_accidents.ipynb: Contiene los códigos y las visualizaciones generadas durante el proceso de transformación, limpieza y el análisis exploratorio de datos.

- AC_accidents_OUTPUTS.csv: Dataset resultado del ETL.

- accidentes_aereos.pbix: Dashboard del proyecto, contiene 1 portada y 4 páginas navegables sobre los análisis y los KPIs.

# [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTNjZWVjNzEtNzg2Zi00YTFkLWI4NmMtM2ViMjc3NjZhOWViIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSection15723a553e111322fc88)
