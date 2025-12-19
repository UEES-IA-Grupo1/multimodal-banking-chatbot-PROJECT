Chatbot Conversacional Multimodal para Servicio al Cliente (Banca Digital)
Este proyecto implementa un asistente inteligente capaz de procesar consultas bancarias a través de texto e imagen, utilizando arquitecturas de vanguardia en Procesamiento de Lenguaje Natural (NLP) y Visión Artificial (CV).

🚀 Características Principales
NLU Avanzado: Reconocimiento de intenciones y extracción de entidades (NER) utilizando modelos basados en BERT.

Gestión de Diálogo con Memoria: Capacidad para mantener el hilo de una conversación y recolectar datos faltantes (Slot Filling).

Procesamiento Multimodal: Fusión de información proveniente de texto y de imágenes (Cheques/ID).

Visión Artificial (OCR): Extracción de texto de documentos bancarios mediante EasyOCR.

Knowledge Graph: Validación de reglas de negocio y existencia de clientes mediante grafos de conocimiento estructurados.

Interfaz Web: Interfaz funcional creada con Gradio.

🛠️ Stack Tecnológico
Lenguaje: Python 3.12

NLP: Hugging Face Transformers (BERT, DistilBERT)

Visión: EasyOCR, OpenCV, PIL

Grafos: NetworkX

Interfaz: Gradio

Entorno: Google Colab

📋 Arquitectura del Proyecto
Módulo NLU: Clasifica la intención del usuario y extrae entidades clave como nombres, montos y números de cuenta.

Módulo de Diálogo: Implementa un DialogueManager que utiliza memoria de sesión para guiar al usuario hasta completar la transacción.

Módulo de Visión: Detecta y lee texto en documentos bancarios (como el archivo SAMPLE CHEQUE.avif).

Módulo de Conocimiento: Cruza la información extraída con un Grafo de Conocimiento para validar límites de crédito y estatus de cliente.

📊 Métricas de Evaluación
El sistema incluye un módulo de evaluación automática que genera reportes de:

Accuracy: Precisión del modelo en la detección de intenciones.

CSAT (Customer Satisfaction Score): Simulación de métricas de satisfacción del cliente basadas en la interacción.

Tiempos de Respuesta: Monitoreo del rendimiento del sistema en milisegundos.

📦 Instalación y Uso
Clona el repositorio:

Bash

git clone https://github.com/tu-usuario/chatbot-multimodal-banca.git
Instala las dependencias:

Bash

pip install transformers datasets easyocr gradio networkx
Ejecuta el notebook en Google Colab o localmente.
