Readme caso 3.

Los archivos del proceso realizado los podrá encontrar en el link 

del GitHub (link), donde encontrara la carpeta con los archivos 

procesados y sin procesar en las carpetas (carpetas).

Los pasos que se realizaron durante la ejecución del código y 

creación del caso son los siguientes:

Se carga el archivo donde se tiene la información (data.csv) por 

medio de código, y delimitando por ";".

Se indican cuales son los 5 valores iniciales que venían en el 

dataframe, al igual que los 5 valores finales.

Luego se clasifican los valores según el tipo al que pertenezcan 

cada uno de ellos.

Entre la columnas del dataframe se validan cuáles son los valores 

NULOS que contiene las columnas, los datos que contengan los 

símbolos "--" fueron reemplazados por NULOS, para luego hacer un 

filtro de las columnas con un porcentaje mayor del 70% de los 

valores en NULOS y eliminarla, igualmente las filas que tengan 

menos de dos elementos son eliminados. 

Los totales de los valores perdidos en el dataframe se agrupan y 

se muestras, al igual que los valores perdidos por columnas.

En la columna "Gender" se reemplazan todos los valores NULOS por 

Unknow. Igualmente los valores NULOS de la columna “Departamento” 

fueron reemplazados por “Bench”.

Todos los valores perdidos de la columna “Overtime” fueron 

reemplazados por "No"

