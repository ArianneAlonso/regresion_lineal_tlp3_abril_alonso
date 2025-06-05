Actividad
1. Investigar y seleccionar un caso en la vida real, en el cual sea posible
aplicar un modelo de regresión lineal. Fundamente la elección.
2. Cree o seleccione un datasets sobre el caso elegido. En el caso de
descargar, realice la limpieza correspondiente. (recomendado:
https://www.kaggle.com ). El datasets debe tener minimo 1000 filas.

el dataset seleccionado se usó para predecir el consumo de energía de electrodomésticos en hogares inteligentes utilizando un modelo de regresión lineal, contiene 100.000 registros con información como Home ID, tipo de electrodoméstico, consumo (kWh), fecha, hora, temperatura exterior, estación y tamaño del hogar. 

Para crear el modelo se realiza un proceso de ordenamiento de ids y fecha

3. Cree y entrene un modelo de regresión lineal con la librería Scikit
Learn.
4. Realice predicciones con el modelo.
5. Cree un gráfico de visualización con Matplotlib que compare los
datos de entrenamiento con los resultados predecidos.

1. crear un entorno virtual
2. instalar las dependencias: pip install pandas scikit-learn matplotlib numpy joblib