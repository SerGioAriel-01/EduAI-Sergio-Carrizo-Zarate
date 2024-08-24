# EduAI: Tutor Educativo Personalizado

## Introducción
EduAI es una herramienta diseñada para proporcionar apoyo académico adicional mediante explicaciones detalladas y material visual educativo. Utiliza los modelos GPT-4 y DALL-E para generar contenido personalizado y visual.

## Problema a Abordar
Muchos estudiantes enfrentan barreras debido a la falta de acceso a tutorías y material visual educativo. Este proyecto busca solucionar estos problemas mediante una herramienta accesible y eficiente.

## Propuesta de Solución
La solución utiliza modelos de IA para generar explicaciones detalladas (GPT-4) y material visual (DALL-E). Esto permite ofrecer una ayuda personalizada y enriquecedora a los estudiantes.

## Mejoras Basadas en Recomendaciones
1. Revisión y Mejora de la Primera Entrega
Se refino la descripción del problema y la solución.
Se incorporo técnicas y métodos aprendidos en las últimas semanas.
Se mejoro la claridad y precisión en la presentación de la propuesta.

2. Optimización de Consultas a la API
Para reducir el costo y optimizar el uso de la API:
Reducir la Frecuencia de Consultas: Agrupa las solicitudes o realiza consultas menos frecuentes si es posible.
Uso Eficiente del Modelo: Aprovecha al máximo cada consulta para obtener toda la información necesaria en una sola llamada.

## Metodología
1. Investigación y preparación del entorno.
2. Implementación y prueba de los modelos de IA.
3. Integración en una aplicación web.
4. Documentación y pruebas finales.

### Descripción del Prompt 
El prompt utilizado en este proyecto está diseñado para generar explicaciones detalladas y material visual educativo utilizando modelos de IA. La idea es ofrecer respuestas claras y gráficos ilustrativos sobre temas específicos, facilitando así el proceso de aprendizaje. 
#### Prompt para Generar Explicaciones 
**El siguiente prompt se usa para generar una explicación detallada sobre un tema educativo específico:** 

prompt = f"Genera una explicación detallada sobre {tema} para un estudiante de nivel {nivel}."

Descripción:
 {tema}: Sustituye por el tema sobre el que se desea una explicación (e.g., "la fotosíntesis").
 {nivel}: Especifica el nivel educativo del estudiante (e.g., "secundario").

Ejemplo de uso:
tema = "la fotosíntesis"
nivel = "secundario"
----------------------
#### Prompt para Generar Imágenes El siguiente prompt se usa para crear una imagen que ilustre un concepto educativo:
prompt = f"Crea un diagrama que ilustre {descripcion}"

explicación:
{descripcion}: Sustituye por una descripción del concepto o proceso que se desea ilustrar (e.g., "el proceso de la fotosíntesis").
Ejemplo de Uso:
descripcion = "el proceso de la fotosíntesis"
-----------------------
Cómo Utilizar los Prompts
Generar Explicaciones:
Modifica el valor de {tema} y {nivel} según el tema y nivel deseado.
Ejecuta el código para obtener una explicación generada por el modelo de IA.

Generar Imágenes:
Modifica el valor de {descripcion} para definir qué gráfico o diagrama deseas.

Ejecuta el código para obtener una imagen generada por el modelo de IA.

Resultados Esperados
Explicaciones: Texto claro y detallado sobre el tema especificado.
Imágenes: Diagramas o gráficos que ilustran el concepto descrito.

## Herramientas y Tecnologías
- **Modelos de IA**: GPT-4 y DALL-E
- **Tecnologías**: API de OpenAI, React, Node.js
- **Documentación**: Jupyter Notebook

