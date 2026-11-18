# Casos de estudio — productos de IA que he construido y lanzado

Construyo productos de IA y sistemas de automatización que funcionan en producción. Estos casos describen el problema, la arquitectura, las restricciones de ingeniería y lo que he poseído, en un nivel útil para ingenieros y seguro para las empresas implicadas.

[English](README.md) · [Português](README.pt.md) · [日本語](README.ja.md)

---

## Taishoku Reset — SaaS japonés de 退職代行

SaaS en producción para 退職代行 (servicios de salida laboral) en Japón, operado por LINE con formularios web seguros, voz/traducción asistida por IA y un flujo operativo interno.

- **Rol:** cofundador y Tech Lead
- **Estado:** en producción desde 2026-11-08
- **Alcance del caso:** contexto de producto, flujo público, arquitectura de cajas, retos de ingeniería y límites de propiedad.
- **No incluido:** código, esquema D1, prompts, lógica de precios, panel de operadores, documentos de incidentes, datos de clientes, métricas de conversión, endpoints internos ni IDs de analítica.

→ **[Leer el caso](case-studies/taishoku-reset/README.es.md)** · [Producto](https://taishokureset.com) · [Instagram](https://www.instagram.com/taishokureset/)

---

## Trabajo de ingeniería seleccionado

| Proyecto | Qué demuestra | Enlaces |
|---|---|---|
| **Intérprete JA ⇄ ES** | Interpretación bidireccional japonés ⇄ español en Linux: PipeWire, Whisper local, traducción Vertex/Gemini, TTS VOICEVOX/Piper, UI GTK4, 185 tests. | [Código](https://github.com/javperman/interprete-ja-es) |
| **video-editor-ai** | Pipeline determinista de edición: `edit_plan.json`, revisiones inmutables, ASR local, subtítulos, PiP, render NVENC y QC. 30 min → ~7,6 min, 2,5 GB pico. | [Código](https://github.com/javperman/video-editor-ai) · [Demo](https://youtu.be/XcZ60adpBms) |
| **FitPrimeLab** | Plataforma de fitness multilingüe con herramientas interactivas y contenido en EN/ES/PT/JA. | [Web](https://fitprimelab.com) · [Código](https://github.com/javperman/fitprimelab-site) |
| **AI Engineering Playbook** | Cómo construyo con agentes: contratos AGENTS.md, planes por fases, checklists, tests, MCP e higiene de secretos. | [Código](https://github.com/javperman/ai-engineering-playbook) |

---

## Qué son estos casos

- Una descripción del **problema**, el **flujo público**, la **arquitectura de cajas** y los **trade-offs** de ingeniería.
- Un registro de lo que poseí y lo que no.
- Un puntero a evidencia pública: webs, repos públicos, páginas legales públicas y canales sociales públicos.

## Qué no son

- No son un volcado de código. El código de clientes y de la empresa sigue privado.
- No contienen datos de clientes, credenciales, métricas internas, prompts, esquemas de base de datos ni pantallas de operadores.
- No reclaman la propiedad de la representación legal, las condiciones comerciales o las relaciones con clientes de una empresa.

---

## Contacto

- Estudio: [Peresotech](https://peresotech.com) — estudio independiente de IA y automatización.
- LinkedIn: [javier-perez-manzano](https://www.linkedin.com/in/javier-perez-manzano)
- Email: [contact@peresotech.com](mailto:contact@peresotech.com)
- Perfil: [github.com/javperman](https://github.com/javperman)
