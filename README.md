# Seminario Bases de Datos
## Trabajo 2
### Resultados "estructura de archivos.ipynb"
Se analizó la estructura interna de los archivos de estudiantes '../SB' y '../Colegios'.
### Resultados entre 2006.ipynb - 2013.ipynb y 2019.ipynb
Análisis de resultados archivos de pruebas estudiantes '../SB'<br>
'SB11_20061.txt', 'SB11_20062.txt'<br>
'SB11_20071.txt', 'SB11_20072.txt'<br>
'SB11_20081.txt', 'SB11_20082.txt'<br>
'SB11_20091.txt', 'SB11_20092.txt'<br>
'SB11_20101.txt', 'SB11_20102.txt'<br>
'SB11_20111.txt', 'SB11_20112.txt'<br>
'SB11_20121.txt', 'SB11_20122.txt'<br>
'SB11_20131.txt', 'SB11_20132.txt'<br>
'SB11_20191.txt'<br>
Análisis de los archivos de colegios que se encuentran en la carpeta '../Colegios'<br>
'SB11-CLASIFI-PLANTELES-2006.txt'<br>
'SB11-CLASIFI-PLANTELES-2007.txt'<br>
'SB11-CLASIFI-PLANTELES-2008.txt'<br>
'SB11-CLASIFI-PLANTELES-2009.txt'<br>
'SB11-CLASIFI-PLANTELES-2010.txt'<br>
'SB11-CLASIFI-PLANTELES-2011.txt'<br>
'SB11-CLASIFI-PLANTELES-2012.txt'<br>
'SB11-CLASIFI-PLANTELES-2013.txt'<br>
**Indices de clasificación**<br>
Indice_Prom = avg(Suma)/max(avg(Suma))<br>
0 < Indice_Prom <= 1<br><br>

Indice_Num = num_est/max(num_est)<br>
0 < Indice_Num <= 1<br><br>

Indice_Total = Indice_Prom X Indice_Num<br>
0 < Indice_Total <= 1<br><br>

avg(Suma):promedio de la suma de puntajes de los estudiantes por colegio<br>
max(avg(Suma)): Máximo Promedio<br>
num_est: número de estudiantes por colegio<br>
max(num_est): máximo número de estudiantes por colegio entre todos los colegios<br>
Indice_Total: tiene en consideraciòn el promedio de las calificaciones y el nùmero de estudiantes<br>
**Conclusiones**<br>
. Por cada uno de los indices se muestra una tabla con los primeros 10 colegios de mayor a menor valor<br>
. No se encontraron coincidencias entre los codigos DANE de los archivos de pruebas de estudiantes y los códigos DANE entregados en los colegios<br>
### Resultados entre 2014.ipynb - 2018.ipynb
Análisis de resultados archivos de pruebas estudiantes '../SB'<br>
'SB11_20141.txt','SB11_20142.txt'<br>
'SB11_20151.txt','SB11_20152.txt'<br>
'SB11_20161.txt','SB11_20162.txt'<br>
'SB11_20171.txt','SB11_20172.txt'<br>
'SB11_20181.txt','SB11_20182.txt'<br>
Análisis de los archivos de colegios que se encuentran en la carpeta '../Colegios'<br>
'SB11-CLASIFI-PLANTELES-20141.txt'<br>
'SB11-CLASIFI-PLANTELES-20142.txt'<br>
'SB11-CLASIFI-PLANTELES-20151.txt'<br>
'SB11-CLASIFI-PLANTELES-20152.txt'<br>
'SB11-CLASIFI-PLANTELES-20161.txt'<br>
'SB11-CLASIFI-PLANTELES-20162.txt'<br>
'SB11-CLASIFI-PLANTELES-20171.csv'<br>
'SB11-CLASIFI-PLANTELES-20172.csv'<br>
'SB11-CLASIFI-PLANTELES-20181.txt'<br>
'SB11-CLASIFI-PLANTELES-20182.txt'<br>
**Conclusiones**<br>
. Se efectua el join entre los archivos de estudiantes y de colegios por el campo indice dane.<br>
. Se crean dos columnas adicionales de comparación 'rank' y 'rankIndiceTotal'.<br> 
. rank: Enumera los colegio de mayor a menor promedio desde los archivos de esudiantes.<br>
. rankIndiceTotal: Enumera los colegios de mayor a menor 'IndiceTotal'.<br>
. Se prensenta una tabla por semestre o anual cuando es posible comparando los rank y rankIndiceTotal para cada colegio.
. En los archivos SB11-CLASIFI-PLANTELES-20141.txt y SB11-CLASIFI-PLANTELES-20142.txt no se encontraron indicadores de  clasificación como IndiceTotal.



