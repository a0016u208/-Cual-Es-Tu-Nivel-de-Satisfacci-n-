# ¿Cual Es Tu Nivel de Satisfaccion?
# Análisis de Sentimiento sobre Netflix
Este README documenta todo el flujo de trabajo realizado en el proyecto de análisis de opiniones sobre Netflix, incluyendo desde la recolección de datos hasta el uso de modelos de inteligencia artificial para el análisis de sentimientos.
El contenido se estructura en cinco secciones principales:
1. Origen de los Datos
2. Preprocesamiento
3. Modelo de Sentimiento
4. Herramientas Empleadas
5. Uso de IA y Prompts

# Flujo del Proyecto
#1. Origen de los Datos
Los datos fueron recolectados a través de una encuesta realizada en *Google Forms*. Las preguntas estaban orientadas a conocer sus opiniones y nivel de satisfacción con aspectos como:

Calidad  de contenido

Relación calidad-precio

Experiencia de usuario

Frecuencia de uso

Las respuestas fueron de tipo texto libre para capturar opiniones auténticas y genuinas de los participantes.


#2. Preprocesamiento
Antes de realizar el análisis de sentimientos, se aplicaron técnicas de limpieza de texto para mejorar la calidad de los datos. Esto incluyó:

Conversión de texto a minúsculas

Eliminación de caracteres especiales

Normalización de espacios

#3. Modelo de Análisis de Sentimiento
Se utilizó un modelo preentrenado basado en la arquitectura Transformers, específicamente uno disponible en la plataforma Hugging Face.
distilbert-base-uncased-finetuned-sst-2-english
(modelo optimizado para clasificación binaria de sentimiento: positivo vs. negativo)
El modelo permitió analizar cada respuesta textual para determinar si la opinión expresada era positiva o negativa, ayudando así a obtener una visión general del sentimiento de los usuarios respecto a Netflix.
