# Shivam Bansal

I build AI gateways, inference tooling, and backend systems.

Most of my public work since February 2021 sits at the intersection of LLM infra, developer tooling, and upstream debugging when production systems get weird.

## What I do

- AI infrastructure for large model workloads, especially B200/H200-era deployment questions
- RAG systems with tenant isolation and operational guardrails that hold up in production
- LLM deployment workflows that are easier to run and debug in production
- Upstream debugging and OSS fixes when tools break under real usage

## Selected projects

### LLMizer
Private LLM deployment orchestration platform with a FastAPI backend, a Next.js dashboard, and LiteLLM as the provider layer. I use it to manage the messy parts of model rollout, provider switching, and day-to-day operations.

### [Audio Craft](https://github.com/ShivamB25/audio-craft-py)
Async-first text-to-speech library built around Gemini TTS workflows. Includes batch processing, multi-speaker dialogue support, and support for 24 languages.

### [HLS Microservice Backend](https://github.com/ShivamB25/hls-microservice-backend)
Video processing backend that converts uploads to HLS, pushes jobs through RabbitMQ, and is set up for containerized deployment.

### [TraceRule](https://github.com/ShivamB25/TraceRule)
An experiment in policy and compliance tooling that turns policy PDFs into structured rules and testable validation flows.

## Open source work since 2021

- [dundee/gdu](https://github.com/dundee/gdu): I started by reporting a panic in empty folders in [issue #273](https://github.com/dundee/gdu/issues/273), then came back with merged work in [#436](https://github.com/dundee/gdu/pull/436), [#437](https://github.com/dundee/gdu/pull/437), [#440](https://github.com/dundee/gdu/pull/440), [#445](https://github.com/dundee/gdu/pull/445), and [#493](https://github.com/dundee/gdu/pull/493) to [#496](https://github.com/dundee/gdu/pull/496). That work was mostly around TUI behavior, safer defaults, navigation, and non-interactive flags.
- [Routr](https://github.com/Routr-technology): on the gateway side, I shipped analytics, RBAC, Auth0 onboarding, audit logging, and security hardening in [gateway #21](https://github.com/Routr-technology/gateway/pull/21), [#24](https://github.com/Routr-technology/gateway/pull/24), [#70](https://github.com/Routr-technology/gateway/pull/70), [#71](https://github.com/Routr-technology/gateway/pull/71), [#72](https://github.com/Routr-technology/gateway/pull/72), and [#85](https://github.com/Routr-technology/gateway/pull/85). On the frontend side, I worked on accessibility, performance, and content cleanup in [frontend #17](https://github.com/Routr-technology/frontend/pull/17), [#19](https://github.com/Routr-technology/frontend/pull/19), [#22](https://github.com/Routr-technology/frontend/pull/22), [#30](https://github.com/Routr-technology/frontend/pull/30), [#31](https://github.com/Routr-technology/frontend/pull/31), and [#32](https://github.com/Routr-technology/frontend/pull/32).
- [Helicone AI Gateway](https://github.com/Helicone/ai-gateway) and [ArgonautAli/arsky](https://github.com/ArgonautAli/arsky): shipped reliability cleanup in [Helicone #180](https://github.com/Helicone/ai-gateway/pull/180) and a TypeScript migration plus CI/linting cleanup in [Arsky #3](https://github.com/ArgonautAli/arsky/pull/3).
- Smaller upstream contributions landed in [Portkey-AI/gateway #1477](https://github.com/Portkey-AI/gateway/pull/1477), [smithery-ai/cli #484](https://github.com/smithery-ai/cli/pull/484), and [anomalyco/models.dev #1095](https://github.com/anomalyco/models.dev/pull/1095).

## How I work

- I like product work, but I am usually most useful in the messy middle: infrastructure, integration problems, reliability fixes, and ugly edge cases.
- When I hit a bug in a tool I depend on, I try to reproduce it properly, file something maintainers can act on, and send a fix upstream if I can.
- Public issue reports I have raised include LiteLLM, OpenCode, Serena, Modal, AWS Neuron samples, Flexprice, and Komf.

I like this part of the job more than I probably should. A lot of my better work starts with reproducing a bug nobody else wants to touch, then either fixing it upstream or building around it.

## Tech I use most

- Languages: TypeScript, Python, Go, Rust, C++
- AI/ML: LiteLLM, OpenAI, Hugging Face, vector search, LoRA workflows, RAG pipelines
- Backend: FastAPI, Node.js, Express, service-to-service APIs
- Frontend: Next.js, React, Tailwind
- Infra: Docker, Kubernetes, Helm, GCP, AWS, Prometheus
- Data: PostgreSQL, MongoDB, Redis, Scylla, ClickHouse

## Elsewhere

- GitHub: [@ShivamB25](https://github.com/ShivamB25)
- LinkedIn: [shivambansal](https://www.linkedin.com/in/shivambansal/)
