Proyecto de Ciencia de Datos: Predicción de Cancelación de Clientes - Telecom X

Objetivo
Predecir qué clientes tienen mayor riesgo de cancelar su contrato con la empresa Telecom X utilizando análisis exploratorio, transformación de datos y modelos de Machine Learning.

Dataset

•	Fuente: Archivo TelecomX_Data.json
•	Cantidad de registros: 6.598 clientes
•	Tipo de problema: Clasificación binaria (Churn: cliente canceló o no el servicio)

Proceso de Trabajo (Trello Backlog)

1.	Preparación de los datos
a.	Extracción del archivo tratado
b.	Eliminación de columnas irrelevantes
c.	Encoding
d.	Verificación de la proporción de cancelación (Churn) 
e.	Balanceo de clases 
f.	Normalización o estandarización

2.	Correlación y selección de variables 
a.	Análisis de correlación
b.	Análisis dirigido

3.	Modelado Predictivo
a.	Separación de datos
b.	Creación de modelos
c.	Evaluación de los modelos

4.	Interpretación y Conclusiones
a.	Análisis de la importancia de las variables
b.	Conclusión 

Conclusiones Finales
El modelo demuestra una buena capacidad predictiva, permitiendo anticipar qué clientes están más propensos a cancelar el servicio. Las variables de contrato, tipo de servicio, forma de pago y antigüedad del cliente son claves para identificar comportamientos de evasión.

Recomendaciones:
•	Ofrecer beneficios a quienes pasen de contrato mensual a anual.
•	Crear alertas tempranas para nuevos clientes con alto riesgo.
•	Evaluar los planes con cargos mensuales elevados.
•	Reforzar retención para clientes con servicio de fibra y pagos electrónicos.

Tecnologías Utilizadas
•	Python + Pandas + NumPy
•	Matplotlib + Seaborn
•	Scikit-learn + imbalanced-learn
•	Google Colab

Estructura del Proyecto
TelecomX_Prediccion_Churn/
-	TelecomX_Data.json
-	telecomx_modelo.ipynb
-	README.md

Autor: Maria C
