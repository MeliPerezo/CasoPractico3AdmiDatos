Readme caso 3.

Los archivos del proceso realizado los podrá encontrar en el link  del GitHub (https://github.com/MeliPerezo/CasoPractico3AdmiDatos). Donde encontrará: la carpeta con los archivos procesados, sin procesar en las carpetas, el desarrollo del caso en python y el archivo README.md.
Se escogió el formato en carpetas para así lograr un estructura más ordenada.Además la nomenclatura utilizada fue la CammelCase. 

Los pasos que se realizaron durante la ejecución del código y creación del caso son los siguientes:

1. Se carga el archivo donde se tiene la información (data.csv) por medio de código, y delimitando por ";".

2. Se indican cuales son los 5 valores iniciales y 5 valores finales del dataframe.

3. Luego se clasifican los valores según el tipo al que pertenezcan cada uno de ellos. (tipo de dato)

4. Entre la columnas del dataframe se validan los valores NULOS que contiene las columnas.

5. Los datos que contengan los  "--" fueron reemplazados por NULOS, para luego hacer un filtro. 

6. Las columnas con un porcentaje mayor del 70% de los valores en NULOS y eliminarla, igualmente las filas que tengan menos de dos elementos son eliminados. 

7. Los totales de los valores perdidos en el dataframe se agrupan y se muestras, al igual que los valores perdidos por columnas.

8. En la columna "Gender" se reemplazan todos los valores NULOS por Unknow. 

10. Igualmente los valores NULOS de la columna "Departamento" fueron reemplazados por "Bench".

11. Todos los valores perdidos de la columna "Overtime" fueron reemplazados por "No". 


