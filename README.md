## Localizar hospitales de CABA en un mapa


A partir del CSV hospitales.csv, se generan dos archivos CSV de salida, uno con pandas (hosp_pandas.csv) y otro con el modulo nativo de python csv (hosp_csv.csv) para ejercitar con ambos. Los archivos de salida contienen solo los siguientes campos en este orden:<br>
latitude<br>
longitude<br>
name<br>
label<br>
Con los correspondientes datos extraídos del CSV original, el campo name tiene que corresponder con la dirección del hospital, y el campo label con el nombre del hospital. El campo latitude y longitude se arma a partir de la columna WKT, la cual contiene las coordenadas que deben adaptarse.<br>
Luego se carga alguno de los dos archivos de salida csv en el sitio https://www.gpsvisualizer.com para poder evaluar la visualización en un mapa, lo cual se descarga por último en caso de requerirar para una presentación.