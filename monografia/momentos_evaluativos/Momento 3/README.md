# Título del Proyecto Seminario de Analítica y Ciencia de Datos ACT02 - Towards Data 

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

Preparación de los datos:
