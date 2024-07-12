# IntelligentGT
En este espacio se sube el código creado para el grupo 

Se debe agregar toda la documentación que ustedes consideren pertinente para la compresión de los modelos usados, la ejecución del código y los resultados obtenidos. 
Puden, si desean, agregar imágenes o resultados obtenidos. 

Recuerden que este readme es su puerta de entrada para su proyecto. 

# Identificador de frutas para la recomendación de recetas

El objetivo de la IA de reconocimiento de frutas para la recomendación de recetas es facilitar una experiencia fluida y enriquecedora en la preparación de alimentos para los usuarios. Esto se logra mediante la identificación precisa de diversas frutas y la recomendación de recetas que aprovechen al máximo sus propiedades nutricionales y gustativas. La IA busca promover una alimentación saludable al proporcionar opciones culinarias variadas y accesibles, adaptadas a diferentes preferencias dietéticas y niveles de habilidad culinaria, con el fin de mejorar la forma en que los usuarios utilizan y disfrutan de las frutas en su vida diaria.

## Tabla de contenidos

1. [Nombre](#Nombre)
2. [Descripción](#descripción)
3. [Arquitectura](#Arquitectura)
4. [Proceso](#Proceso)
5. [Funcionalidades](#Funcionalidades)
6. [Estado del proyecto](#EstadoDelProyecto)
7. [Agradecimientos](#Agradecimientos)


* Nombre del proyecto

Identificador de frutas para la recomendación de recetas

* Breve descripción del proyecto

El objetivo de la IA de reconocimiento de frutas para la recomendación de recetas es facilitar una experiencia fluida y enriquecedora en la preparación de alimentos para los usuarios. Esto se logra mediante la identificación precisa de diversas frutas y la recomendación de recetas que aprovechen al máximo sus propiedades nutricionales y gustativas. La IA busca promover una alimentación saludable al proporcionar opciones culinarias variadas y accesibles, adaptadas a diferentes preferencias dietéticas y niveles de habilidad culinaria, con el fin de mejorar la forma en que los usuarios utilizan y disfrutan de las frutas en su vida diaria.

* Arquitectura del proyecto + imagen

* Proceso de desarrollo:

- Fuente del dataset:

https://www.kaggle.com/datasets/moltean/fruits

- Limpieza de datos (img que lo valide)

- Manejo excepciones/control errores

El modelo cuenta con un control en que informa si la fruta detectada no existe o si por el contrario en algún caso no tiene una receta

- ¿Qué modelo de Machine Learning están usando?

Se está utilizando un modelo de red neuronal convolucional (CNN) para el reconocimiento de imágenes. Las CNN son un tipo de deep learning

- Estadísticos (Valores, gráficos, …)

Tenemos una gráfica de precisión del modelo y de pérdida del modelo, mostrando constantemente los cambios en cada época tanto en la precisión de entrenamiento como en la precisión de validación y la perdida de entramiento junto con la perdida de validación respectivamente.

- Métrica(s) de evaluación del modelo

accuracy, val_accuracy, loss, val_loss y categorical_crossentropy como función de pérdida útil para modelos con multiples clases como es el caso
