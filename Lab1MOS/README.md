# Instrucciones de ejecución

En el archivo de **JupyterLab** se implementaron los modelos utilizando **Pyomo**, cargando como insumo los archivos `datosProblema1.csv`, `datosProblema2.csv` y `datosProblema3.csv`. Cada archivo contiene la información de entrada con la misma estructura definida en el enunciado del laboratorio, organizada en formato tabular, separado por ; y sin el uso de tildes para evitar inconsistencias en la lectura. 

Para ejecutar el código, basta con abrir el notebook en JupyterLab, asegurarse de que los archivos CSV se encuentren en el mismo directorio de trabajo y correr secuencialmente cada celda del notebook. Esto permitirá cargar los datos, formular los modelos, resolverlos con el solver disponible (**GLPK**) y visualizar tanto los resultados numéricos como las gráficas generadas.
