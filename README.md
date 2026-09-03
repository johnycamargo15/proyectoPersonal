# Lisander_AIMA Bot

Bot de Telegram para practicar prospección comercial con un prospecto simulado por IA.

## Variables de entorno

- `TELEGRAM_BOT_TOKEN`
- `OPENAI_API_KEY`

En Render:

- Build Command: `npm install`
- Start Command: `npm start`
- Root Directory: vacío (el proyecto está en la raíz del repositorio)

El servicio configura automáticamente el webhook usando `RENDER_EXTERNAL_URL`.

## Primera versión

- `/start`
- 🎯 Practicar prospección
- Dificultad fácil / media / difícil
- 📊 Evaluación de la conversación
- Menú de Telegram

La sesión de práctica se mantiene temporalmente en memoria. En una siguiente versión se puede añadir base de datos, historial, prospectos, seguimientos y entrada por voz.
