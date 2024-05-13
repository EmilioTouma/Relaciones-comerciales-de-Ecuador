# Relaciones-comerciales-de-Ecuador


**Descripción del proyecto:** Este proyecto tiene como objetivo comprender las relaciones comerciales de Ecuador a profundidad. Con el fin de mejorar la comprensión del comercio internacional de nuestro país, utilizamos diversas herramientas de visualización. Una de las principales conclusiones es que Ecuador posee relaciones comerciales que no están respaldadas por tratados comerciales. De esa forma, con el fin de aumentar el intercambio mutuamente beneficioso entre Ecuador y estos países, se debería buscar mayores alianzas y firmas de tratados. 
<br />
Las bases utilizadas provienen de la SENAE. Contienen información sobre las exportaciones e importaciones bajo régimen simplificado.
<br />

**Descripción de las carpetas:**
<br />
*-->Raw data:*
<br />
Contiene los datos de exportaciones, importaciones y diccionarios para el año 2023.
<br />
*-->Analysis:*
<br />
Códigos para realizar el proceso de análisis de datos.
<br />

**Instrucciones sobre cómo instalar y ejecutar el código:** Para ejecutar los códigos debe descargar las bases de la carpeta "Raw data". A partir de esto, usted puede descargar los códigos de la carpeta "Analysis" y compilarlos en su computadora. Es fundamental que modifique la dirección para cargar las bases según dónde guardó las bases. Por ejemplo, en uno de los archivos se utiliza la siguiente línea de código:
<br />
data_export = pd.read_csv("/content/drive/MyDrive/Data Science/Raw data/senae_exportacion_simplificado_enero_noviembre_2023.csv",delimiter='|').<br /> Por lo cual, para evitar un error, usted debe modificar el link, según el lugar donde guardó la base "senae_exportacion_simplificado_enero_noviembre_2023.csv".

<br />
**Lista de dependencias o librerías necesarias:** pandas, plotly.express, pycountry-convert y  plotly.
