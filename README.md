🤖 Chatbot Conversacional Multimodal para Servicio al Cliente (Banca Digital)

Este proyecto implementa un asistente inteligente de atención al cliente para banca digital, capaz de procesar consultas por texto e imagen, integrando NLP avanzado, visión artificial y grafos de conocimiento para soportar decisiones operativas en tiempo real.

El objetivo es automatizar interacciones bancarias complejas, reducir fricción operativa y mejorar la experiencia del cliente mediante IA explicable y escalable.

🚀 Funcionalidades Clave
🧠 NLU Avanzado

Clasificación de intenciones (Intent Recognition)

Extracción de entidades (NER): nombres, montos, cuentas

Modelos basados en BERT / DistilBERT (Hugging Face)

💬 Gestión de Diálogo con Memoria

Dialogue Manager con estado de sesión

Slot Filling automático para recolectar información faltante

Conversaciones coherentes y orientadas a objetivo

🖼️ Procesamiento Multimodal

Integración de texto + imagen

Análisis de documentos bancarios (cheques, identificaciones)

🔍 Visión Artificial (OCR)

Extracción de texto mediante EasyOCR

Preprocesamiento con OpenCV y PIL

Soporte para archivos como SAMPLE_CHEQUE.avif

🕸️ Knowledge Graph

Validación de reglas de negocio

Verificación de clientes, estatus y límites

Implementación con NetworkX

🌐 Interfaz Web

Interfaz funcional construida con Gradio

Uso interactivo en navegador (ideal para demos y MVP)

🛠️ Stack Tecnológico
Componente	Tecnología
Lenguaje	Python 3.12
NLP	Hugging Face Transformers (BERT, DistilBERT)
Visión	EasyOCR, OpenCV, PIL
Grafos	NetworkX
Interfaz	Gradio
Entorno	Google Colab
🧩 Arquitectura del Sistema
1️⃣ Módulo NLU

Clasifica la intención del usuario

Extrae entidades clave (NER)

Base para el flujo de decisión

2️⃣ Módulo de Diálogo

Gestión de contexto por sesión

Control del flujo conversacional

Validación de datos antes de ejecutar acciones

3️⃣ Módulo de Visión

Lectura automática de documentos bancarios

OCR optimizado para imágenes reales

4️⃣ Módulo de Conocimiento

Grafo de clientes y reglas de negocio

Validación de:

Existencia del cliente

Estatus

Límites y restricciones

📊 Métricas de Evaluación

El sistema incluye evaluación automática orientada a negocio:

Accuracy
Precisión en la detección de intenciones

CSAT (Customer Satisfaction Score)
Simulación de satisfacción del cliente basada en la interacción

Tiempo de Respuesta (ms)
Medición de performance del sistema

▶️ Ejecución del Proyecto

Abrir el notebook en Google Colab

Instalar dependencias

Ejecutar las celdas en orden

Acceder a la interfaz Gradio generada

El proyecto está diseñado como MVP funcional, fácilmente extensible a producción.

📌 Casos de Uso

Atención al cliente en banca digital

Validación automática de cheques/documentos

Asistentes virtuales financieros

Prototipos de IA conversacional multimodal

📈 Roadmap (Mejoras Futuras)

Integración con APIs bancarias reales

Persistencia de sesiones en base de datos

Modelos multimodales end-to-end

Despliegue en cloud (AWS / GCP / Azure)

