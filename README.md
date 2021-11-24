Trabajo Final - Métodos Cumputacionales Para Política Públicas <br>
Nombre: Cindy Lorena Sáenz Robayo <br>
Correo electrónico: cindyl.saenz@urosario.edu.co <br>

**ARCHIVOS EN DRIVE** https://drive.google.com/drive/u/0/folders/1yrV9DUjWtduCqwy9vs4pm0xCBENPjnL5

**PROPUESTA**

**Descripción y Motivación**

Está en desarrollo una tesis doctoral que pretende “Explicar por qué ha sido posible la implementación de políticas de desarrollo alternativo en Tumaco del 2010 al 2020 a pesar de la debilidad de las capacidades del Estado en este territorio”. 
Esta propuesta de investigación se sustenta en un marco teórico con tres conceptos fundamentales: implementación de las políticas, capacidades estatales y territoriales y desarrollo alternativo.
1. El abordaje de la implementación de las políticas públicas como un proceso adaptativo.
2. Tener en cuenta las capacidades territoriales que permiten poner en marcha.
3. Estrategias de desarrollo alternativo en contextos de alta complejidad y débil capacidad estatal.

Por lo anterior, y con las herramientas como Python, tableau y web scraping se pretende desarrollar los siguiente:

1.	Análisis de la Política: Se efectuará web scraping a las fuentes relacionas con el Acuerdo de Paz (Pagina de la Presidencia de la República) y al Programa Nacional de Sustitución de Cultivos Ilícitos. Se verificará la relación y mención de los siguientes términos descritos en el marco conceptual de la investigación, tales como: implementación, capacidades (capacidades específicamente del estado), desarrollo, drogas, cultivos, antidrogas, entre otras.

2.	Análisis del municipio: Efectuar un análisis y contexto del municipio de San Andres de Tumaco, verificando el índice del desempeño municipal MDM desde el 2010 al 2020, extrayendo la información de la página web del Departamento Nacional de Planeación, así como el IDF (Índice de Desempeño Fiscal). También se efectuan los mapas de información geográfica con la información de los cultivos ilícitos.

Lo anterior, con el objetivo de caracterizar el caso de estudio para efectos instrumentales del proyecto de investigación.

**MÉTODOS UTILIZADOS**

**1. BASE DE DATOS** 


Se utiliza pandas para recoletar, almacenar, limpiar y organizar los siguientes datos:
   
**1.1.** Índice del desempeño municipal MDM desde 2010-2025 <br>
https://www.dnp.gov.co/programas/desarrollo-territorial/Estudios-Territoriales/Indicadores-y-Mediciones/Paginas/desempeno-integral.aspx


**1.2.** Índice del desempeño municipal MDM desde 2016-2020 <br> https://portalterritorial.dnp.gov.co/AdmInfoTerritorial/MenuInfoTerrEstMDM

**1.3.** Índice de desempeño fiscal IDF desde 2010-2020 <br>
https://www.dnp.gov.co/programas/desarrollo-territorial/Estudios-Territoriales/Indicadores-y-Mediciones/Paginas/desempeno-fiscal.aspx

**1.4.** Cultivos ilícitos de Coca en héctareas <br>
https://www.minjusticia.gov.co/programas-co/ODC/Paginas/SIDCO-departamento-municipio.aspx


<br> 

**2. NLTK** 


Se utiliza NLTK para recolectar, almacenar e indentificar los terminos: implementación, políticas, públicas, capacidades, territoriales, desarrollo, alternativo, sustitución, erradicación, coca, generación, ingresos, cultivos, ilícito, ilícitos, a los siguientes textos:

**2.1** Acurdo de Paz <br> https://www.cancilleria.gov.co/sites/default/files/Fotos2016/12.11_1.2016nuevoacuerdofinal.pdf

**2.2** Programa Nacional de Sustitución de Cultivos Ilícitos <br> http://es.presidencia.gov.co/normativa/normativa/DECRETO%20896%20DEL%2029%20DE%20MAYO%20DE%202017.pdf

**2.3** Plan de Desarrollo Departamental Nariño 2016-2019 <br> http://www.2016-2019.narino.gov.co/inicio/index.php/gobernacion/plan-de-desarrollo/354-plan-de-desarrollo-departamental-narino-corazon-del-mundo-2016-2019

**2.4** Plan de Desarrollo Departamental Nariño 2020-2023 <br>

**2.5** Plan de Desarrollo Municipal de San Andres de Tumaco 2016-2019 <br>

**2.6** Plan de Desarrollo Municipal de San Andres de Tumaco 2020-2023 <br>


<br> 

**3. WEB SCRAPING**

Se analizan los discursos mensuales que se encuentran en la página Web Archive

**3.1** Discrusos Presidenciales 2010 - 2015 en la página Web Archive https://web.archive.org/ de la página DAPRE http://wsp.presidencia.gov.co/Discursos/2014/Paginas/Agosto.aspx


**RESULTADOS**

A continuación un resumen del los cultivos ilícitos en Colombia del año 2010 - 2020 en el siguiente link se observan todos los datos  <br>
https://public.tableau.com/app/profile/cindy.lorena.s.enz.robayo/viz/HectaraCultivosIlcitosColombia2010-2020/CultivosIlcitos?publish=yes <br>

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/Colombia2010.jpg)


A continuación un resumen del los cultivos ilícitos del Municipio de San Andres de Tumaco del año 2010 - 2020 en el siguiente link se observan todos los datos  <br>
https://public.tableau.com/app/profile/cindy.lorena.s.enz.robayo/viz/HectaraCultivosIlcitosColombia2010-2020/CultivosIlcitos?publish=yes <br>


![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/Tumaco2010.jpg)

Se detalla a contInuación el detalle de los cultivos e indices del Municipio: <br>

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/Municipio.jpg)

Utilizando NLTK a continuación el detalla y comparación de los diferentes textos:

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/PlandesarolloD.jpg)

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/PlandesarolloM.jpg)

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/Acuerdo.jpg)

Se evaluaron 606 discursos en el periodo de 2010-2015 (antes de la firma del Acuerdo) evaluando las palabras del Presidente implementación, políticas, públicas, capacidades, territoriales, desarrollo, alternativo, sustitución, erradicación, coca, generación, ingresos, cultivos, ilícito, ilícitos 

![Image](https://github.com/LorenaSaenzRobayo/MCPP-2021-II/blob/main/Web.jpg)

**CONCLUSIONES** <br><br>

1. Los datos sustentan la pertinencia de la pregunta de investigación. <br><br>


2. San Andres de Tumaco ha sido el municipio con mayor presencia de cultivos ilícitos específicamente de coca, sin embargo, a pesar de sus debilidades institucionales, después de la implementación del programa de sustitución, el municipio ha logrado disminuir sus cultivos ilícitos en los últimos 3 años.<br><br>

3. Teniendo en cuenta los planes departamentales y municipales, es necesario adoptar medidas que fortalezcan a los departamentos y municipios en sus capacidades territoriales


**REFERENCIAS**

https://www.dnp.gov.co/programas/desarrollo-territorial/Estudios-Territoriales/Indicadores-y-Mediciones/Paginas/desempeno-integral.aspx <br>
https://portalterritorial.dnp.gov.co/AdmInfoTerritorial/MenuInfoTerrEstMDM <br>
https://www.dnp.gov.co/programas/desarrollo-territorial/Estudios-Territoriales/Indicadores-y-Mediciones/Paginas/desempeno-fiscal.aspx <br>
https://www.minjusticia.gov.co/programas-co/ODC/Paginas/SIDCO-departamento-municipio.aspx <br>
https://www.cancilleria.gov.co/sites/default/files/Fotos2016/12.11_1.2016nuevoacuerdofinal.pdf <br>
http://es.presidencia.gov.co/normativa/normativa/DECRETO%20896%20DEL%2029%20DE%20MAYO%20DE%202017.pdf <br>
http://www.2016-2019.narino.gov.co/inicio/index.php/gobernacion/plan-de-desarrollo/354-plan-de-desarrollo-departamental-narino-corazon-del-mundo-2016-2019 <br>
https://web.archive.org/ <br>
http://wp.presidencia.gov.co/Discursos/2015/Paginas/Diciembre.aspx <br>
http://es.presidencia.gov.co/discursos <br>
https://github.com/smatallana/presidential_speeches/blob/master/speeches_analysis.ipynb <br>
https://www.unodc.org/ 

