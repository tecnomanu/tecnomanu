# Hola, soy Manu (TecnoManu)

**Tech Lead en Bytetravel / Globely. Full-stack developer. Builder de herramientas AI, MCP, ChatGPT Apps y utilidades open source.**

Trabajo con TypeScript, JavaScript, Python, PHP, Laravel, Angular, React, NestJS, FastAPI, Docker, MCP y agentes AI.

Hoy foco principal:

- AI tooling real para producto
- herramientas local-first
- automatización con agentes
- project context compartido para equipos AI
- ChatGPT Apps y MCP servers

[![GitHub followers](https://img.shields.io/github/followers/tecnomanu?style=flat&label=Followers)](https://github.com/tecnomanu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manuel%20Bru%C3%B1a-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuelbrunia/)
[![Instagram](https://img.shields.io/badge/Instagram-@tecno.manu-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/tecno.manu/)

---

## Ahora construyendo

### Agent Project Context

Estoy empujando **APC (Agent Project Context)**: una convención abierta para guardar contexto durable de proyectos AI en una carpeta `.apc/`, sin duplicar todo entre `.claude/`, `.cursor/`, `.codex/`, `.opencode/`, etc.

La idea simple:

> un proyecto, una capa de contexto compartida.

- Web: https://agentprojectcontext.com/
- Repo: https://github.com/agentprojectcontext/agentprojectcontext

APC no reemplaza MCP. APC organiza contexto del proyecto. MCP conecta herramientas externas.

---

## Proyectos destacados

### Remove Background Local

Herramienta open source para quitar fondos de imágenes localmente.

Corre en tu máquina. No sube imágenes a servidores externos. Sin API. Sin cuenta. Sin límites de uso. Incluye UI web, cola de procesamiento, sesiones persistentes, descarga masiva, varios formatos de salida, app desktop con Electron y modelos como ISNet/BiRefNet.

- Repo: https://github.com/tecnomanu/remove-background-local
- npm: https://www.npmjs.com/package/remove-background-local

```bash
npx -y remove-background-local
npx -y remove-background-local@latest desktop install
```

### Bytetravel ChatGPT App

Participé en creación/publicación de la app de **Bytetravel** en directorio de Apps de ChatGPT.

Aprendizaje fuerte: una ChatGPT App real no es solo integrar herramientas. Hay que diseñar casos de uso, flujos conversacionales, resultados esperados, consistencia de respuestas, testing, revisiones y cómo ChatGPT decide cuándo usar cada tool.

Trabajo actual: **Tech Lead en Globely**, proyecto Bytetravel.

### Puppeteer Server MCP

Servidor MCP para automatización segura de navegador usando Puppeteer.

Permite navegación real, screenshots, clicks, formularios, evaluación JS, logs de consola, whitelist de dominios, límites, timeouts y audit logging.

- Repo: https://github.com/tecnomanu/puppeteer-server

### Video Docs Builder

Skill/herramienta para generar videos documentales de apps web.

Combina Playwright, TTS y FFmpeg para grabar flujos, narrarlos y armar videos sincronizados. Útil para demos, onboarding, QA y documentación viva.

- Repo: https://github.com/tecnomanu/video-docs-builder

### MCP Telegram Agent

MCP server para enviar notificaciones a Telegram desde agentes AI.

Incluye onboarding guiado, verificación de configuración y ejecución vía `npx`.

- Repo: https://github.com/tecnomanu/mcp-telegram-agent

### Bootstrap Project MCP

MCP server para generar proyectos completos desde templates y prompts guiados.

Nació como demo técnica y evolucionó como base para crear proyectos MCP, React, Astro, NestJS y otros stacks desde asistentes compatibles.

- Repo: https://github.com/tecnomanu/bootstrap-project-mcp

### Control Cursor With Hand

Experimento de computer vision para controlar cursor con gestos de mano.

Proyecto hobby, pero conecta con accesibilidad, interfaces naturales y visión por computadora.

- Repo: https://github.com/tecnomanu/control-cursor-with-hand

---

## MCP & agentes

- [Agent Rules Kit](https://github.com/tecnomanu/agent-rules-kit) — CLI para scaffoldear reglas y guías MCP listas para agentes en IDEs y terminales.
- [Agent Rules Kit MCP](https://github.com/tecnomanu/agent-rules-kit-mcp) — servidor MCP companion para ejecutar reglas desde agentes.
- [Puppeteer Server](https://github.com/tecnomanu/puppeteer-server) — automatización browser safe-by-default.
- [MCP Telegram Agent](https://github.com/tecnomanu/mcp-telegram-agent) — notificaciones Telegram desde MCP.
- [Bootstrap Project MCP](https://github.com/tecnomanu/bootstrap-project-mcp) — creación de proyectos desde templates guiados.
- [PAMPA](https://github.com/tecnomanu/pampa) — semantic code memory + servidor MCP para búsqueda precisa en repos.

---

## AI / local-first tools

- [Remove Background Local](https://github.com/tecnomanu/remove-background-local) — quitar fondos localmente, sin subir imágenes.
- [Video Docs Builder](https://github.com/tecnomanu/video-docs-builder) — grabación automática de documentación en video.
- [Control Cursor With Hand](https://github.com/tecnomanu/control-cursor-with-hand) — cursor controlado con gestos.

---

## Templates / starters

- [Multitenant NestJS API base](https://github.com/tecnomanu/multitenant-nestjs-api-base) — boilerplate SaaS multi-tenant con auth, seeds y tooling DevOps.
- [Panel base Angular + Lumen](https://github.com/tecnomanu/panel-base-frontend-api) — base frontend/backend para panels internos.
- [Bootstrap Project MCP](https://github.com/tecnomanu/bootstrap-project-mcp) — templates guiados desde agentes.

---

## Docker / backend

- [PHP8 FPM + Nginx + Supervisor](https://github.com/tecnomanu/docker-php8-laravel-nginx-supervisor) — imagen Alpine optimizada para Laravel/Lumen.
- [PHP 7.4 variantes](https://github.com/tecnomanu/docker-php74-laravel-nginx-supervisor)
- [PHP 7.4 + MongoDB](https://github.com/tecnomanu/docker-php74-mongodb-nginx-supervisor)

---

## Microservicios

- [Gateway (KrakenD)](https://github.com/tecnomanu/microservice-gateway)
- [Users (NestJS)](https://github.com/tecnomanu/microservice-users)
- [Auth](https://github.com/tecnomanu/microservice-authentication)
- [Redis Service](https://github.com/tecnomanu/microservice-redis)

---

## Charlas y demos

- **Nerdearla 2025** — demo MCP/n8n/IA con Carlos Pereyra.
- [Nerdearla Agenda MCP](https://github.com/tecnomanu/nerdearla-agenda-mcp) — servidor MCP usado para compartir agenda interactiva en tiempo real.
- Charla: https://www.youtube.com/watch?v=NKPeVDFvDys

---

## Contacto

- GitHub: https://github.com/tecnomanu
- LinkedIn: https://www.linkedin.com/in/manuelbrunia/
- Instagram: https://www.instagram.com/tecno.manu/
- Web: https://incubit.com.ar/

> Build fast. Ship simple. Learn always.
