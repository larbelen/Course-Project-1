## Introducción

Esta asignación utiliza datos de
<a href="http://archive.ics.uci.edu/ml/"> UC Irvine Máquina
Aprender </a> repositorio, un repositorio popular para aprendizaje automático
conjuntos de datos. En particular, vamos a utilizar el "hogar individual
el consumo de energía eléctrica del conjunto de datos ", que he puesto a disposición en
el sitio web del curso:


* <B> Conjunto de datos </ b>: <a </a> consumo de energía [20Mb]

* <B> Descripción </ b>: Las mediciones de consumo de energía eléctrica en
un hogar con una tasa de muestreo de un minuto durante un período de casi
4 años. Los diferentes magnitudes eléctricas y algunos valores sub-medición
están disponibles.


Se toman las siguientes descripciones de las 9 variables en el conjunto de datos
de
<a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption"> UCI
sitio web </a>:

<Ol>
<Li> <b> Fecha </ b>: Fecha en formato dd / mm / aaaa </ li>
<Li> <b> Tiempo </ b>: el tiempo en formato hh: mm: ss </ li>
<Li> <b> Global_active_power </ b>: hogares poder global minutos promediada activa (en kilovatios) </ li>
<Li> <b> Global_reactive_power </ b>: corriente doméstica mundial minutos promediada reactiva (en kilovatios) </ li>
<Li> <b> Tensión </ b>: minutos promediada tensión (en voltios) </ li>
<Li> <b> Global_intensity </ b>: hogar intensidad de corriente minuto promediada global (en amperios) </ li>
<Li> <b> Sub_metering_1 </ b>: energía submedición No. 1 (en vatios-hora de energía activa). Corresponde a la cocina, que contiene principalmente un lavavajillas, horno y microondas (platos calientes no son eléctricos, pero alimentados gas). </ Li>
<Li> <b> Sub_metering_2 </ b>: energía submedición Nº 2 (en vatios-hora de energía activa). Se corresponde con el cuarto de lavado, que contiene una lavadora, una secadora de pelo, una nevera y una luz. </ Li>
<Li> <b> Sub_metering_3 </ b>: energía submedición No. 3 (en vatios-hora de energía activa). Corresponde a un calentador de agua eléctrico y un acondicionador de aire. </ Li>
</ Ol>

## Cargando los datos


