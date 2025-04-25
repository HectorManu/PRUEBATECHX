# Aquí está la resolución de una prueba técnica para TechX
> Debido a la extención de la prueba para volver pesado el repositorio se mantendrá por separado con su respectivo link en cada carpeta de este mismo, puden consultar cada Carpeta y su respectivo proyecto a continuación.

## 🧭 Repositorio Central

Este repositorio contiene enlaces a otros proyectos de la prueba:

## 🔗 Sub-repositorios

- 📁 [PARTE 1 – OCR en Web App Full Stack (Python + TypeScript) BACKEND](https://github.com/HectorManu/PARTE-1-BACK)
- 📁 [PARTE 1 – OCR en Web App Full Stack (Python + TypeScript) FRONTEND](https://github.com/HectorManu/PARTE-1)
- 📁 [PARTE 2 – Web Scraping con Endpoint]()
- 📁 [PARTE 3 – Chatbot + NLP + Consulta Dinámica]()
- 📁 [PARTE 4 – IA: CNN + API Predictiva]()
- 📁 [PARTE 5 – RESOLUCIÓN DE PROBLEMAS & DECISION MAKING (AI & Automation Lead)]()


## 🧩 PARTE 1 – OCR en Web App Full Stack (Python + TypeScript) COMPLETADO

<video src="assets/demo.webm" width="600" autoplay loop muted></video>


---
Objetivo:
Construir una pequeña aplicación que permita subir una imagen de un recibo, procesarla con OCR (Tesseract) y visualizar los datos detectados.

Requisitos:

API con FastAPI: /upload-ocr (POST)
Frontend con React + TypeScript: vista con campo para subir archivo y mostrar texto.
OCR usando Pytesseract o equivalente.
Validación de errores (imagen no legible, OCR vacío, etc.)
Evaluación:

Correcta comunicación entre frontend y backend.
Limpieza del texto extraído y robustez.
Buen manejo de errores y UX mínima funcional.

---


## 🧩 PARTE 2 – Web Scraping con Endpoint
Objetivo:
Crear un script que haga scraping de una web de productos (libros, electrónicos, etc.) y exponga los datos por API.

Requisitos:

Web scraping (con BeautifulSoup o Scrapy).
Guardar productos en base de datos (título, precio, categoría, rating).
Endpoint /products con filtros (precio, nombre, categoría).
Evaluación:

Robustez del scraping (manejo de páginas vacías o caídas).
Estructura clara de la base de datos.
Filtros funcionales y bien documentados.

---


## 🧩 PARTE 3 – Chatbot + NLP + Consulta Dinámica
Objetivo:
Desarrollar un chatbot simple con NLP que responda preguntas sobre una base de datos ficticia con dos tablas: Compradores y Deudores.

Requisitos:

Tabla compradores: (id, nombre, total_compras)
Tabla deudores: (id, nombre, monto_adeudado)
Endpoint /chatbot que entienda preguntas como:
¿Quiénes son los mejores compradores?
¿Cuáles son los deudores más altos?
¿Cuántos compradores hay?
Sugerencias técnicas:

Puede usarse spaCy, transformers o lógica propia de intents.
La respuesta debe incluir resultados claros, ordenados y en lenguaje natural.
Evaluación:

Detección de intención y extracción de entidades.
Precisión en la consulta y lenguaje de respuesta.
Diseño modular para escalar futuras preguntas.

---

## 🧩 PARTE 4 – IA: CNN + API Predictiva

Objetivo:
Entrenar una red neuronal convolucional (CNN) y exponerla como servicio web.

Requisitos:

Dataset sugerido: MNIST o CIFAR-10.
Modelo entrenado en PyTorch o TensorFlow.
API /predict-image que reciba imagen en base64 y devuelva etiqueta.
Documentación del modelo, arquitectura, precisión y justificación.
Evaluación:

Correcta arquitectura y rendimiento del modelo.
Exposición API y respuesta rápida.
Buen uso de dependencias y versión reproducible.

---

## 🧠 PARTE 5 – RESOLUCIÓN DE PROBLEMAS & DECISION MAKING (AI & Automation Lead)
Objetivo:
Evaluar capacidad de liderazgo técnico, resolución de ambigüedad, análisis de tradeoffs, y diseño de sistemas escalables.

🧠 Caso 1: Integración multiplataforma

Tu equipo necesita integrar un sistema de scraping de productos que alimente tanto un chatbot (para consultas de clientes) como un dashboard (para analistas de negocio). El cliente quiere respuestas en tiempo real, pero el scraping toma entre 5 y 10 segundos por producto nuevo. ¿Cómo diseñarías esta arquitectura?
🔹 Entrega esperada:

Diagrama del sistema propuesto.
Estrategia de asincronía, colas o almacenamiento intermedio.
Justificación técnica.
🧠 Caso 2: Fallo del OCR en producción

Después de lanzar el OCR en producción, se reportan errores en más del 35% de los recibos escaneados (mal reconocimiento de fechas y totales). ¿Cómo abordarías esta situación como líder del área?
🔹 Entrega esperada:

Diagnóstico probable (modelo, input, UX).
Solución técnica propuesta.
Priorización de tareas y comunicación con stakeholders.
🧠 Caso 3: Chatbot con datos erróneos

El chatbot devuelve información desactualizada o incorrecta sobre compradores frecuentes. El modelo NLP funciona, pero las respuestas están mal. ¿Cómo organizarías el diagnóstico y corrección?
🔹 Entrega esperada:

Hipótesis de errores (fuente de datos, cacheo, entrenamiento).
Estrategia para testing, logging y validación.
Propuesta para monitoreo y mejora continua.
📁 ENTREGABLES GENERALES

Repositorio con carpetas por sección.
README.md con:
Instrucciones de instalación.
Razonamientos detrás de decisiones clave.
Carpeta docs/ con:
Diagrama de arquitectura.
Documentación de modelo CNN.
Respuestas de resolución de problemas.
