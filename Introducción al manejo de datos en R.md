# Introducción al manejo de datos en R

Dentro de los muchos cursos disponibles de Data Science, Machine learning, estadística, etc. probablemente el gran olvidado suele ocupar al menos el 50% del tiempo, el *manejo de datos* o *data management*. Y es que en ambiente laboral nos vamos a encontrar siempre con estos capítulos asociados a las competencias de un científico de datos o analista de datos.

- **Bases de datos**: Generalmente las empresas tienen sus datos guardados en servidores y los analistas acceden a ellos mediante diferentes interfaces, no se suelen utilizar archivos de datos sino más bien una infraestructura.
  - Relacionales: generalmente en lenguaje SQL como MySql, Oracle, etc.
  - No relacionales o NoSQL: como MongoDB
- **Visualización de datos**
  - Tableros: Tableau, Shiny o PowerBI
  - Gráficos: Matplotlib, ggplot, Plotly, etc.
- **Manejo de datos**: Si bien es posible lograr un alto nivel de manejo en la interfaz de las bases de datos como SQL, la capacidad  de tratar datos es limitada, sobre todo cuando se desea preparar los datos para el análisis estadístico o en machine learning, esta es la parte del trabajo del analista o científico de datos en dónde se debe contar con buenas competencias.
  - Excel: Lo más básico e indispensable, será el canal de comunicación entre todos porque es por lejos el formato para manejo de datos más conocido. Limitaciones tiene muchas, comenzando por la limitada cantidad de registros que permite, sólo 1 millon de filas
  - Python: Muy usado, mediante Numpy y Pandas para el manejo de datos. No es lo más amigable ni versatil pero permite hacer todo lo necesario
  - R: este lenguaje de programación está pensado para el manejo estadístico, razón por la cual dispone de muchisimas alternativas para el manejo de datos, por lo pronto el sistema base es muy parecido a pandas de python, pero además tiene tidyverse con dplyr que es muy sencillo de usar y data.table que es la mejor alternativa para grandes bases de datos.
- **Machine learning**: ya en este apartado tenemos muchas alternativas, la mayoría implementadas tanto en R como en Python
- **Estadística**: aun cuando algo se puede hacer en Python, no es su fuerte, para esto lo más recomendable es Stata o R.

> Diferencias entre Científico de datos y Analista de datos: Si bien esto no es una certeza absoluta se acerca bastante.
>
> * Científico de datos: Especialista en desarrollar modelos de machine learning y estadística. Sus principales herramientas serán SQL (o bases de datos), programar en R o Python y manejo en Excel.
> * Analista de datos: Especialista en desarrollar herramientas de análisis orientada a la inteligencia de negocios. Sus principales herramientas son el manejo de bases de datos que expresa con herramientas de visualización de datos como Tableau, por supuesteo también Excel.
> * Si bien ambos perfiles son evidentes, ambos deben dominar herramientas de administración de datos, tanto si es en SQL, R o Pandas/Numpy.

## Objetivos del tutorial

Si bien la mayoría de cursos presentan el análisis de datos como una serie consecutiva de herramientas lo más habitual las tareas en general no son tantas, el resto es incorporar elementos de programación por lo pronto pensemos en una tabla cualquiera, con filas y columnas.











































