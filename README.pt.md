# Estudos de caso — produtos de IA que construí e lancei

Construo produtos de IA e sistemas de automação que funcionam em produção. Estes estudos descrevem o problema, a arquitetura, as restrições de engenharia e o que eu assumi, em um nível útil para engenheiros e seguro para as empresas envolvidas.

[English](README.md) · [Español](README.es.md) · [日本語](README.ja.md)

---

## Taishoku Reset — SaaS japonês de 退職代行

SaaS em produção para 退職代行 (serviços de saída profissional) no Japão, operado por LINE com formulários web seguros, voz/tradução assistida por IA e um fluxo operacional interno.

- **Papel:** cofundador e Tech Lead
- **Status:** em produção desde 2026-11-08
- **Escopo do estudo:** contexto de produto, fluxo público, arquitetura em caixas, desafios de engenharia e limites de responsabilidade.
- **Não incluído:** código, schema D1, prompts, lógica de preços, painel de operadores, documentos de incidentes, dados de clientes, métricas de conversão, endpoints internos ou IDs de analytics.

→ **[Ler o estudo](case-studies/taishoku-reset/README.pt.md)** · [Produto](https://taishokureset.com) · [Instagram](https://www.instagram.com/taishokureset/)

---

## Trabalho de engenharia selecionado

| Projeto | O que demonstra | Links |
|---|---|---|
| **Intérprete JA ⇄ ES** | Interpretação bidirecional japonês ⇄ espanhol no Linux: PipeWire, Whisper local, tradução Vertex/Gemini, TTS VOICEVOX/Piper, UI GTK4, 185 testes. | [Código](https://github.com/javperman/interprete-ja-es) |
| **video-editor-ai** | Pipeline determinístico de edição: `edit_plan.json`, revisões imutáveis, ASR local, legendas, PiP, render NVENC e QC. 30 min → ~7,6 min, 2,5 GB de pico. | [Código](https://github.com/javperman/video-editor-ai) |
| **FitPrimeLab** | Plataforma de fitness multilíngue com ferramentas interativas e conteúdo em EN/ES/PT/JA. | [Site](https://fitprimelab.com) · [Código](https://github.com/javperman/fitprimelab-site) |
| **AI Engineering Playbook** | Como construo com agentes: contratos AGENTS.md, planos por fases, checklists, testes, MCP e higiene de segredos. | [Código](https://github.com/javperman/ai-engineering-playbook) |

---

## O que estes estudos são

- Uma descrição do **problema**, do **fluxo público**, da **arquitetura em caixas** e dos **trade-offs** de engenharia.
- Um registro do que assumi e do que não assumi.
- Um ponteiro para evidência pública: sites, repositórios públicos, páginas legais públicas e canais sociais públicos.

## O que eles não são

- Não são um dump de código. O código de clientes e da empresa continua privado.
- Não contêm dados de clientes, credenciais, métricas internas, prompts, schemas de banco ou telas de operadores.
- Não reivindicam a propriedade da representação legal, das condições comerciais ou das relações com clientes de uma empresa.

---

## Contato

- Estúdio: [Peresotech](https://peresotech.com) — estúdio independente de IA e automação.
- LinkedIn: [javier-perez-manzano](https://www.linkedin.com/in/javier-perez-manzano)
- Email: [contact@peresotech.com](mailto:contact@peresotech.com)
- Perfil: [github.com/javperman](https://github.com/javperman)
