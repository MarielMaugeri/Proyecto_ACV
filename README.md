# Proyecto final Neoland: Modelo predictivo para ACV

## Contexto
  Según la Organización Mundial de la Salud (OMS), el ictus es la segunda causa principal de muerte a nivel mundial, responsable de aproximadamente el 11% del total de muertes. 

## Datos
  Este conjunto de datos se utiliza para predecir la probabilidad de que un paciente sufra un ictus según parámetros como el sexo, la edad, diversas enfermedades y el tabaquismo. Se cuenta con 5110 
filas, y cada una proporciona información relevante sobre el paciente. 
  Los datos se encuentran en un csv descargado de [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  

  La información con la que se cuenta es la siguiente: 
    id: identificador único. 
    gender: género del paciente. 
    age: edad del paciente. 
    hypertension: 0 si el paciente no tiene hipertensión, 1 si la tiene. 
    heart_disease: 0 si el paciente no tiene alguna enfermedad cardíaca, 1 si tiene. 
    ever_married: “Yes” o “No”, si ha estado casado. 
    work_type: Tipo de trabajo.  
    Residence_type: Zona de residencia. “Rural” o “Urbana”. 
    avg_glucose_level: Promedio de glucosa en sangre. 
    bmi: Índice de masa corporal. 
    smoking_status: Condición de fumador.  
    stroke: 1 si el paciente tuvo un ictus, 0 si no. 

## Resumen de resultados de los modelos
<img width="1367" height="220" alt="image" src="https://github.com/user-attachments/assets/dd369fc4-6869-48ba-bb4e-455961aa1113" />

## Conclusiones
  De los tres modelos evaluados se podría considerar como mejor al modelo KNN, ya que fue el que presentó mejor recall (igual que random forest pero mejora un poco la precisión). 
  Sin embargo no es un resultado muy bueno, por lo que se podría seguir probando modelos más avanzados, y sobre todo buscar aumentar el tamaño del dataset ya que al estar tan poco representado 
el grupo positivo es muy difícil mejorar la sensibilidad sin caer en una disminución de la precisión. 
  Por último también se pudo confirmar que la probabilidad de sufrir un ictus aumenta 
principalmente con la edad.
