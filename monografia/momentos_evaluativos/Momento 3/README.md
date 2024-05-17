# Título del Proyecto Seminario de Analítica y Ciencia de Datos ACT02 - Towards Data 

## Como ejecutar los scripts

1. Descargue el archivo funciones.py en el repositorio "Momento 3" [especializacion/monografia momentos_evaluativos/Momento 3/utils/funciones.py](https://github.com/Causil/especializacion/blob/main/monografia/momentos_evaluativos/Momento%203/utils/funciones.py)
2. Abra el siguiente enlace para cargar el notebook desde Google Colab:
[Collaboratory](https://colab.research.google.com/github/Causil/especializacion/blob/main/
monografia/momentos_evaluativos/Momento%203/ME03-G10-%5B1038129159%5D-%5B98761437%5D.ipynb) 

3. Agregue el archivo funciones.py al entorno de directorios del Google Colab abierto en el segundo paso.

4. Corra todo el Google Colab

Exploration and Preparation

 Descripción de la Actividad 1. 
Cada grupo deberá describir detalladamente los datos originales disponibles para su proyecto, incluyendo formatos, distribución de los datos, descripción de las columnas, y cualquier etiquetado disponible


El equipo desarrollador de Auralac, nos dio acceso a la nube mediante un usuario de AWS con ciertos privilegios, que nos permiten interactuar con la base de datos no relacional DynamoDB, se está tramitando un diccionario de datos en el cual se explique cada contexto de las variables, por el momento se tiene una relación de las tablas sobre las cuales se tiene acceso para el proyecto, en las cuales se identifica el tipo de colecciones y su relación con la planta de producción.

Se dispone de dos fuentes de datos:
1. Información de la energía activa y reactiva por hora para el periodo comprendido entre febrero de 2020 y mayo de 2023. Estos datos son proporcionados directamente por la empresa prestadora de servicios de energía eléctrica y son un instrumento para el control del pago de la facturación mensual. Se cuenta con un archivo en excel por año. Cada archivo contiene cuatro variables de las cuales se tiene información para cada hora:
    - Energía Activa Consumo (kWh)
    - Energía Activa Generación (kWh)
    - Energía Reactiva Inductiva (kVarh)
    - Energía Reactiva Capacitiva (kVarh)