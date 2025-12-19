# 🤖 Chatbot Conversacional Multimodal para Servicio al Cliente (Banca Digital)

Este proyecto implementa un **asistente inteligente para banca digital**, capaz de procesar
consultas bancarias a través de **texto e imagen**, integrando arquitecturas de vanguardia en
**Procesamiento de Lenguaje Natural (NLP)** y **Visión Artificial (CV)**.

El objetivo es **automatizar interacciones bancarias complejas**, reducir fricción operativa
y mejorar la experiencia del cliente mediante **IA explicable y escalable**.

---

## 🚀 Características Principales

### 🧠 NLU Avanzado
- Reconocimiento de intenciones (Intent Recognition)
- Extracción de entidades (NER): nombres, montos y cuentas
- Modelos basados en **BERT / DistilBERT** (Hugging Face)

### 💬 Gestión de Diálogo con Memoria
- Capacidad para mantener el contexto conversacional
- Recolección automática de información faltante (Slot Filling)
- Conversaciones coherentes y orientadas a objetivo

### 🖼️ Procesamiento Multimodal
- Fusión de información proveniente de **texto + imágenes**
- Análisis de documentos bancarios (cheques e identificaciones)

### 🔍 Visión Artificial (OCR)
- Extracción de texto de documentos bancarios
- Implementación mediante **EasyOCR**
- Soporte para archivos como `SAMPLE_CHEQUE.avif`

### 🕸️ Knowledge Graph
- Validación de reglas de negocio
- Verificación de existencia y estatus de clientes
- Implementación con grafos de conocimiento estructurados

### 🌐 Interfaz Web
- Interfaz funcional desarrollada con **Gradio**
- Acceso vía navegador para pruebas y demostraciones
<img width="1737" height="557" alt="image" src="https://github.com/user-attachments/assets/54d6ef54-8fa2-43e2-a356-f3275f37afa3" />

---

## 🛠️ Stack Tecnológico

- **Lenguaje:** Python 3.12  
- **NLP:** Hugging Face Transformers (BERT, DistilBERT)  
- **Visión:** EasyOCR, OpenCV, PIL  
- **Grafos:** NetworkX  
- **Interfaz:** Gradio  
- **Entorno:** Google Colab  

---

## 📋 Arquitectura del Proyecto

### 1️⃣ Módulo NLU
- Clasifica la intención del usuario
- Extrae entidades clave como nombres, montos y números de cuenta

### 2️⃣ Módulo de Diálogo
- Implementa un `DialogueManager`
- Utiliza memoria de sesión para guiar al usuario hasta completar la transacción

### 3️⃣ Módulo de Visión
- Detecta y lee texto en documentos bancarios
- Preprocesamiento de imágenes para OCR

### 4️⃣ Módulo de Conocimiento
- Cruza la información extraída con un **Grafo de Conocimiento**
- Valida límites de crédito y estatus del cliente

---

## 📊 Métricas de Evaluación

El sistema incluye un módulo de evaluación automática que genera reportes de:

- **Accuracy**  
  Precisión del modelo en la detección de intenciones

- **CSAT (Customer Satisfaction Score)**  

