# Proyecto final Neoland: Modelo predictivo para ACV

## Contexto
&nbsp;&nbsp;&nbsp;&nbsp;Según la Organización Mundial de la Salud (OMS), el ictus es la segunda causa principal de muerte a nivel mundial, responsable de aproximadamente el 11% del total de muertes. 

## Datos
&nbsp;&nbsp;&nbsp;&nbsp;Este conjunto de datos se utiliza para predecir la probabilidad de que un paciente sufra un ictus según parámetros como el sexo, la edad, diversas enfermedades y el tabaquismo. Se cuenta con 5110 filas, y cada una proporciona información relevante sobre el paciente.  
&nbsp;Los datos se encuentran en un csv descargado de [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  

&nbsp;&nbsp;&nbsp;&nbsp;La información con la que se cuenta es la siguiente:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id: identificador único.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;gender: género del paciente.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;age: edad del paciente.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;hypertension: 0 si el paciente no tiene hipertensión, 1 si la tiene.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;heart_disease: 0 si el paciente no tiene alguna enfermedad cardíaca, 1 si tiene.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ever_married: “Yes” o “No”, si ha estado casado.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;work_type: Tipo de trabajo.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Residence_type: Zona de residencia. “Rural” o “Urbana”.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;avg_glucose_level: Promedio de glucosa en sangre.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bmi: Índice de masa corporal.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;smoking_status: Condición de fumador.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;stroke: 1 si el paciente tuvo un ictus, 0 si no.  

## Resumen de resultados de los modelos
<img width="1367" height="220" alt="image" src="https://github.com/user-attachments/assets/dd369fc4-6869-48ba-bb4e-455961aa1113" />

## Conclusiones
&nbsp;&nbsp;&nbsp;&nbsp;De los tres modelos evaluados se podría considerar como mejor al modelo KNN, ya que fue el que presentó mejor recall (igual que random forest pero mejora un poco la precisión).  
&nbsp;&nbsp;&nbsp;&nbsp;Sin embargo no es un resultado muy bueno, por lo que se podría seguir probando modelos más avanzados, y sobre todo buscar aumentar el tamaño del dataset ya que al estar tan poco representado el grupo positivo es muy difícil mejorar la sensibilidad sin caer en una disminución de la precisión.  
&nbsp;&nbsp;&nbsp;&nbsp;Por último también se pudo confirmar que la probabilidad de sufrir un ictus aumenta 
principalmente con la edad.
