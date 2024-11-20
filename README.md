# ChatBot Básico con NLP

Este proyecto es un chatbot simple que utiliza técnicas básicas de procesamiento de lenguaje natural (NLP) para responder preguntas comunes. El chatbot responde utilizando un enfoque basado en reglas y también se puede integrar con un modelo preentrenado de Hugging Face para generar respuestas más dinámicas.

## Características
- **Respuestas predefinidas**: El chatbot tiene un conjunto de respuestas fijas para preguntas comunes como "Hola", "¿Qué es IA?", y "Adiós".
- **Procesamiento de texto**: Usa NLTK para tokenizar y limpiar el texto del usuario.
- **Modelo IA**: Utiliza un modelo preentrenado de Hugging Face (DistilBERT) para proporcionar respuestas más sofisticadas basadas en preguntas formuladas por el usuario.
- **Interfaz en consola**: El chatbot interactúa con el usuario a través de la consola, donde el usuario puede hacer preguntas y recibir respuestas.

## Tecnologías Utilizadas
- **Python**
- **NLTK**: Biblioteca de procesamiento de lenguaje natural.
- **Transformers (Hugging Face)**: Para integrar modelos preentrenados como DistilBERT.
  
## Instalación
Para ejecutar este chatbot, primero debes instalar las dependencias necesarias. En Google Colab, puedes hacer esto ejecutando:

```bash
!pip install nltk transformers
