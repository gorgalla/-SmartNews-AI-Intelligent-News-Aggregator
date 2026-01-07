SmartNews AI es una herramienta de línea de comandos (CLI) desarrollada en Python que permite centralizar la búsqueda de noticias globales y generar resúmenes inteligentes utilizando modelos de lenguaje de OpenAI (GPT).

Este proyecto fue diseñado aplicando prácticas de Python profesional, priorizando la modularidad, el tipado estático y el manejo robusto de errores.
🛠️ Tecnologías y Herramientas

    Lenguaje: Python 3.12+

    Gestor de Dependencias: UV (Extremadamente rápido y moderno)

    APIs Externas: NewsAPI (Recolección de datos) y OpenAI API (Procesamiento de texto)

    Calidad de Código: Ruff (Linter y Formatter)

    Entorno: Variables de entorno para gestión de credenciales sensibles.

✨ Características Principales

    Búsqueda Dinámica: Uso de *args y **kwargs para crear un cliente de API flexible.

    Procesamiento Inteligente: Integración con IA para calcular tiempos de lectura y resumir artículos.

    Código Pythónico: Implementación de list comprehensions, filtros y mapas para una manipulación de datos eficiente.

    Robustez: Manejo de excepciones personalizadas para errores de conexión o límites de API.

    Documentación: Código totalmente documentado bajo el estándar PEP 257 y uso de Type Hints para facilitar el mantenimiento.

🚀 Instalación y Uso
Requisitos Previos

Tener instalado UV. Si no lo tienes, puedes usar pip.

    Clonar el repositorio:
    Bash

git clone https://github.com/tu-usuario/smartnews-ai.git
cd smartnews-ai

Configurar variables de entorno: Crea un archivo .env en la raíz del proyecto:
Code snippet

NEWS_API_KEY=tu_api_key_aqui
OPENAI_API_KEY=tu_api_key_aqui

Instalar dependencias y ejecutar:
Bash

    uv sync
    uv run main.py

🏗️ Arquitectura del Proyecto

El código sigue el principio de Responsabilidad Única (SRP):

    api_client.py: Maneja la comunicación pura con NewsAPI.

    processor.py: Contiene la lógica de filtrado y procesamiento de datos.

    ai_service.py: Encapsula las llamadas a OpenAI.

    main.py: Punto de entrada que coordina el flujo de la aplicación.

📈 Aprendizajes Técnicos

Durante el desarrollo de este proyecto, profundicé en:

    La importancia de los entornos virtuales para la reproducibilidad.

    El uso de modificadores de formato avanzados en f-strings para presentaciones limpias en consola.

    Gestión profesional de errores con bloques try/except/finally para liberar recursos adecuadamente.
