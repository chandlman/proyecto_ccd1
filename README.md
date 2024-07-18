Se trabajó con la base de datos de la NBA, donde a la misma se le hicieron transformaciones necerarias para aplicar PCA y LazyClassifier. Para PCA, se eligieron solo las variables continuas y se estandarizaron los datos
para aplicar PCA. Para Lazy se eliminó la columna de texto, que poseía los nombres de los jugadores, dejando las variables numéricas para los modelos. Finalmente para optimizar hiperparámetros se uso GridSearchCV 
y se entrenó el modelo con los mejores hiperparámetros, para posteriormente evaluarlo el modelo.
