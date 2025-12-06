# cyberbot-open

CyberBot Open es una herramienta de ciberseguridad conversacional, open source y colaborativa. Integra múltiples motores de IA y frameworks de chatbot, pensada para desarrolladores y administradores web que requieren asesoría avanzada en seguridad informática.

**Enfoque ético:** No asiste en la creación de malware ni software dañino, pero sí responde todo lo referente a ciberseguridad y desarrollo responsable, incluyendo temas avanzados, auditoría, pentesting, defensa e integración de herramientas.

## Características

- Multi-modelo: Rasa (Python), Botpress, Langchain.js + modelos Mistral, GPT4All, DeepSeek, Copilot
- API REST y WebSocket para integración web o con otras herramientas
- Docker-ready: instalación fácil y portátil
- Interoperabilidad entre bots/IA
- Sin filtros restrictivos, pero con capa de protección ética anti-malware

## Instalación Rápida

```bash
git clone https://github.com/Falconmx1/cyberbot-open.git
cd cyberbot-open
docker-compose up --build
```

## Estructura Recomendada

```
cyberbot-open/
├── frontend/
├── backend/
├── rasa/
├── botpress/
├── docker-compose.yml
├── README.md
├── .gitignore
├── LICENSE
```

## Licencia

Software bajo Licencia MIT.
