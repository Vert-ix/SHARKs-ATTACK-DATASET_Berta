# SHARKs-ATTACK-DATASET_Berta

Proyecto limpieza de datos

Introdución.

El objetivo del proyecto es limpiar y preparar los datos para el análisis. Se proporciona un excel con un conjunto de datos desordenados y complejos por naturaleza. Se pretende refinar y reestructurar conjuntos de datos hasta un estado utilizable para pasar a la etapa de análisis de datos.

Proceso.

En primer lugar, trabajaremos con unos datos descargados de la página web Global Shark Attacks https://www.kaggle.com/teajay/global-shark-attacks. 

Limpieza de los datos:
- Crear copia de seguridad.

- Renombrar columnas quitando espacios, al principio, al final y entre medias. Y mayúsculas por minúsculas.

- Borrado de todos los duplicados de las filas.
- Borrado de todos los index que tienen valor nulo en las tres columnas de Area, Country y Location conjuntamente.

- Examinar el porcentaje de ataques por países para ver cuales son los tres países con mayor número de ataques. Y a partir de ahí trabajar solamente con los datos de esos tres países. Usa, Australia y South África.

- Borrado de valores nulos en la columna Sex y en la columna Fatal, dejando solamente valores reales y analizables.

    Yes/No para la columna Fatal.
    Masculino/Femeneino para la columna Sex.
    
- Limpieza de la columna Year. He descartado todos los años por debajo de 1900, ya que los datos pueden ser inconclusos.

- Eliminación de todos los valores invalidos de la columna Type.

- Eliminación de valores nulos en las columnas.

- Claseficación de la columna Species en 26 especies de tiburones más desconocidos.

- Limpieza de la columna Date, dejando solo en mes porque el año ya aparece en la columna Year.

- Limpieza de la columna Age, eliminando valores nulos o poco precisos y redondeando valores.

- Clasificación de actividades en la columna Activity en 13 categorias y otros.

- Por último he cambiado los valores object por categoricos para que ocupen menos espacio en memoria.

- Exportar el archivo como DataLimpieza_csv.

