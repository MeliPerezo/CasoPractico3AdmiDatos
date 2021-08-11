Readme caso 3.

Los archivos del proceso realizado los podr� encontrar en el link 

del GitHub (https://github.com/MeliPerezo/CasoPractico3AdmiDatos), donde encontrará la carpeta con los archivos 

procesados y sin procesar en las carpetas (carpetas) y el desarrollo del caso en python.

Los pasos que se realizaron durante la ejecuci�n del c�digo y 

creaci�n del caso son los siguientes:

Se carga el archivo donde se tiene la informaci�n (data.csv) por 

medio de c�digo, y delimitando por ";".

Se indican cuales son los 5 valores iniciales que ven�an en el 

dataframe, al igual que los 5 valores finales.

Luego se clasifican los valores seg�n el tipo al que pertenezcan 

cada uno de ellos.

Entre la columnas del dataframe se validan cu�les son los valores 

NULOS que contiene las columnas, los datos que contengan los 

s�mbolos "--" fueron reemplazados por NULOS, para luego hacer un 

filtro de las columnas con un porcentaje mayor del 70% de los 

valores en NULOS y eliminarla, igualmente las filas que tengan 

menos de dos elementos son eliminados. 

Los totales de los valores perdidos en el dataframe se agrupan y 

se muestras, al igual que los valores perdidos por columnas.

En la columna "Gender" se reemplazan todos los valores NULOS por 

Unknow. Igualmente los valores NULOS de la columna �Departamento� 

fueron reemplazados por �Bench�.

Todos los valores perdidos de la columna �Overtime� fueron 

reemplazados por "No". 
Además la nomenclatura utilizada fue la CammelCase y todos los archicos fueron separados en carpetas, para así lograr un estructura más ordenada. 

