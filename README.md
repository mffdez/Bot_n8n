<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2CA5E0&height=160&section=header&text=Telegram%20AI%20Bot&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Conversaciones%20inteligentes%20desde%20Telegram&descSize=16&descAlignY=58&descColor=e0f0ff" width="100%"/>
</div>

<br/>

<div align="center">

[![Made with n8n](https://img.shields.io/badge/Built%20with-n8n-orange?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![Powered by ChatGPT](https://img.shields.io/badge/Powered%20by-ChatGPT-10a37f?style=for-the-badge&logo=openai)](https://openai.com/)
[![Telegram Bot](https://img.shields.io/badge/Platform-Telegram-2CA5E0?style=for-the-badge&logo=telegram)](https://telegram.org/)

</div>

<br/>

---

## Descripción

**Bot de Telegram** es un bot que permite mantener conversaciones fluidas con modelos de lenguaje avanzados (LLMs) como ChatGPT directamente desde Telegram. Sin necesidad de abrir el navegador ni navegar por interfaces complejas — simplemente escribe tu mensaje y recibe una respuesta inteligente al instante.

---

## Características

<div align="center">

| Característica | Descripción |
|:-:|:--|
| **Conversación natural** | Interactúa con ChatGPT como si fuera un contacto más en Telegram |
| **Respuestas rápidas** | El bot procesa y responde en cuestión de segundos |
| **Conversaciones continuas** | Encadena múltiples mensajes de forma fluida |
| **Modelo GPT integrado** | Aprovecha toda la potencia de los modelos de OpenAI |

</div>

---

## Arquitectura

El bot está construido sobre **n8n**, una plataforma de automatización de flujos de trabajo. El flujo sigue los siguientes pasos:

<br/>

<div align="center">

```
┌─────────────────────────────────┐
│        Mensaje de Telegram      │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  Telegram Trigger               │
│  Escucha mensajes entrantes     │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  API de ChatGPT                 │
│  Procesa y razona la respuesta  │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  Respuesta al usuario           │
│  Entregada de forma inmediata   │
└─────────────────────────────────┘
```

</div>

---

## Tecnologías

<div align="center">

[![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange?style=flat-square&logo=n8n)](https://n8n.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-Language%20Model-10a37f?style=flat-square&logo=openai)](https://openai.com/)
[![Telegram](https://img.shields.io/badge/Telegram-Bot%20API-2CA5E0?style=flat-square&logo=telegram)](https://core.telegram.org/bots/api)

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2CA5E0&height=100&section=footer" width="100%"/>
</div>
