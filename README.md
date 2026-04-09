# 🧠 LexIA: Asistente Inteligente de Lectura Dinámica

> **Estado del Proyecto:** Fase de Planificación (Candidatura Beca ANFAIA - Verano 2026).
> **Licencia:** Apache 2.0 (Open Source).

LexIA es una extensión de navegador de código abierto diseñada para ayudar a personas con dislexia a superar barreras cognitivas en textos web estandarizados, mediante Inteligencia Artificial y Procesamiento de Lenguaje Natural (NLP).

## 🎯 El Problema
El entorno digital actual está diseñado bajo un estándar de uniformidad textual que penaliza a los usuarios con dislexia, generando alta carga cognitiva, fatiga y menor comprensión. Las herramientas actuales suelen limitarse a cambios visuales (contraste, tipografía), pero no abordan la barrera sintáctica y léxica.

## 💡 La Solución
LexIA adapta tanto la carga visual como cognitiva de los textos en tiempo real. Mediante IA, el asistente procesa el contenido de la página y ofrece:
* **Simplificación léxica:** Sustitución de vocabulario complejo por sinónimos comunes.
* **Separación visual:** Espaciado dinámico de bloques sintácticos para evitar la pérdida de línea.
* **Resúmenes automáticos:** Para facilitar la comprensión global del texto.

## 🛠️ Stack Tecnológico
Para garantizar que el proyecto sea 100% gratuito, eficiente y de código abierto, la arquitectura cliente-servidor se compone de:

* **Frontend (Extensión):** JavaScript (Vanilla), HTML, CSS (Manifest V3) y Web Speech API.
* **Backend (API):** Python con FastAPI.
* **IA / NLP:** * `spaCy` para análisis morfosintáctico.
  * `Hugging Face Transformers` (arquitectura mT5) para simplificación y resúmenes.

## 📅 Roadmap de Desarrollo (MVP en 8 Semanas)
* **Mes 1:** Desarrollo del Core, manipulación del DOM (extensión), setup de FastAPI y procesamiento sintáctico inicial.
* **Mes 2:** Integración de IA generativa para simplificación léxica, refactorización, pruebas de estrés y publicación open-source.
