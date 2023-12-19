# Evaluación Final del Módulo 3 de Adalab
En este repositorio podrán encontrar la evaluación final del módulo 3 de Adalab

Para llevar a cabo dicha prueba hemos contado con la información contenida en dos csvs: Customer Flight Activity y Customer Loyalty History. Cada uno de ellos cuenta con datos relevantes sobre los clientes de esta compañía aérea canadiense y que son de gran utilidad para dicha aerolínea. 
Con dicha información nos hemos enfrentado a una serie de ejercicios, divididos en tres fases, que hemos planteado a través de un Jupyter Notebook.

FASE 1: Exploración y Limpieza
1. Exploración Inicial:
Realiza una exploración inicial de los datos para identificar posibles problemas, como valores nulos, atípicos o datos faltantes en las columnas relevantes.
Utiliza funciones de Pandas para obtener información sobre la estructura de los datos, la presencia de valores nulos y estadísticas básicas de las columnas involucradas.
Une los dos conjuntos de datos de la forma más eficiente.
2. Limpieza de Datos:
Elimina o trata los valores nulos, si los hay, en las columnas clave para asegurar que los datos estén completos.
Verifica la consistencia y corrección de los datos para asegurarte de que los datos se presenten de forma coherente.
Realiza cualquier ajuste o conversión necesaria en las columnas (por ejemplo, cambiar tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.

FASE 2: Visualización
Usando las herramientas de visualización que has aprendido durante este módulo, contesta a las siguientes gráficas usando la mejor gráfica que consideres:
1.¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?
2.¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los clientes?
3.¿Cuál es la distribución de los clientes por provincia o estado?
4.¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
5.¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
6. ¿Cómo se distribuyen los clientes según su estado civil y género?

FASE 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo
Objetivo del Ejercicio: Utilizando un conjunto de datos que hemos compartido, se busca evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. Para ello, los pasos que deberas seguir son:
1. Preparación de Datos:
Filtra el conjunto de datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.
2. Análisis Descriptivo:
Agrupa los datos por nivel educativo y calcula estadísticas descriptivas básicas (como el promedio, la desviación estandar, los percentiles) del número de vuelos reservados para cada grupo.
3. Prueba Estadística:
Realiza una prueba de A/B testing para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.
