
# Consumo de agua en la Ciudad de México

El siguiente proyecto se refiere al análisis de datos de la base de consumo de agua para 2019, obtenida de la [página oficial].

[1]: https://datos.cdmx.gob.mx/explore/dataset/consumo-agua/table/

## Prerequisitos

Se tiene que tener instalado Python 3. Las versiones específicas de paquetes se encuentran recopiladas en el archivo **requirements.txt**. Estos requerimientos tienen que ser instalados para poder correr el análisis.

## Instalación

El paquete de archivos desarrollados son los siguientes:
- load_data.py
- clean_data.py
- transform_data.py
- eda.py
- geda.py
- main_file.py

El archivo principal para correr el análisis de datos es el archivo **main_file.py**. A este archivo se le tienen que hacer los cambios para especificar la ruta del archivo que contiene los datos y su ruta. 

Se deben seguir los siguientes pasos:

 1. Descargar la base de datos desde [página oficial] con un nombre *my_data.csv* 
 2. Todos los archivos del paquete deben ser descargados, no necesariamente al mismo folder
 3. Abrir el archivo *main_file.py* y realizar las siguientes acualizaciones:
      3.1 Actualizar el nombre del archivo en la linea indicada por **# Update data file name**. Nota que el nombre se debe encontrar entre comillas, por ejemplo *"consumo-agua.csv"*.
      3.2. Actualizar la ruta donde se encuentra el archivo *my_data.csv*, indicada en la linea **# Update path to data file**. Por ejemplo, puedes actualizar la ruta como *"/home/bj/Documents/IntroDataScience/eda_hw/Data"*. Observe que la ruta no contiene el **/** final.
      
## Reporte final

https://bcjg23.github.io/Consumo_de_Agua_CDMX_2019/index.html
