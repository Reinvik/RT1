# 🧠 RT1 - Gemini AI Integration Test

![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=flat&logo=node.js&logoColor=white)
![Google Gemini](https://img.shields.io/badge/AI-Google_Gemini-8E75B2?style=flat&logo=google&logoColor=white)

> **Entorno de pruebas rápidas para la integración de Google Gemini API (Multimodal).**

---

## ℹ️ Descripción

Este repositorio contiene scripts de prueba y prototipos para validar capacidades de la API de Google Gemini antes de integrarlas en la suite principal **Nexus Jarvis**.

## 🧪 Pruebas Incluidas

- **Texto Generativo**: Pruebas de prompts básicos y zero-shot.
- **Visión Multimodal**: Scripts para enviar imágenes locales a Gemini Vision y extraer datos estructurados (OCR).
- **Chat Contextual**: Pruebas de historial de conversación.

## 🚀 Ejecución

```bash
# 1. Instalar dependencias
npm install

# 2. Configurar API Key
# Renombrar .env.example a .env.local y poner tu clave de Google AI Studio.

# 3. Correr pruebas
npm run dev
```

---
**Autor:** Reinvik (Ariel Mella)
